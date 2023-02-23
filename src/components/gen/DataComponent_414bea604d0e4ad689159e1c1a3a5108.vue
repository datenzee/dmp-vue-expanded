<script setup>
import * as $rdf from 'rdflib'
import IterativeContainer from '@/components/vo/IterativeContainer.vue'
import Dataset from './Dataset.vue'
// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])

const predicate = $rdf.sym('https://w3id.org/dcso/ns/core#hasDataset')
// <custom-code>
// </custom-code>
</script>
<template>
    <IterativeContainer
        :graph="graph"
        :depth="depth"
        :object="object"
        :predicate="predicate"
        v-slot="slotProps"
    >
        <Dataset :graph="graph" :depth="depth" :object="slotProps.object" />
    </IterativeContainer>
</template>