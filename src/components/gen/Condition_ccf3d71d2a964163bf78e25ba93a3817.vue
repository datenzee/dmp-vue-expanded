<script setup>
import * as $rdf from 'rdflib'
import Container_8eba13da7bdf4f919ea4db52196fec54 from './Container_8eba13da7bdf4f919ea4db52196fec54.vue'

import Container_b3ee93378cab4437896a722cbc239b28 from './Container_b3ee93378cab4437896a722cbc239b28.vue'

// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])


const predicate = $rdf.sym('https://w3id.org/dcso/ns/core#sensitiveData')
const value = ''

const compare = (object) => props.graph?.match(object, predicate)[0]?.object.value == value
// <custom-code>
// </custom-code>
</script>
<template>
    <div>
        <template v-if="compare(object)">
            <Container_8eba13da7bdf4f919ea4db52196fec54 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
        <template v-else>
            <Container_b3ee93378cab4437896a722cbc239b28 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
    </div>
</template>