<script setup>
import * as $rdf from 'rdflib'
import Container_8a9b8a4459ff440684dd71e116809e57 from './Container_8a9b8a4459ff440684dd71e116809e57.vue'

import Container_b5b9a55a6cff48f2bf75d6f17eaef759 from './Container_b5b9a55a6cff48f2bf75d6f17eaef759.vue'

// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])


const predicate = $rdf.sym('https://w3id.org/dcso/ns/core#personalData')
const value = ''

const compare = (object) => props.graph?.match(object, predicate)[0]?.object.value == value
// <custom-code>
// </custom-code>
</script>
<template>
    <span>
        <template v-if="compare(object)">
            <Container_8a9b8a4459ff440684dd71e116809e57 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
        <template v-else>
            <Container_b5b9a55a6cff48f2bf75d6f17eaef759 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
    </span>
</template>