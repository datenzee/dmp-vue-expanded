<script setup>
import * as $rdf from 'rdflib'
import Container_fa6510ef16284343bd891c58b7ad1f20 from './Container_fa6510ef16284343bd891c58b7ad1f20.vue'

import Condition_ccf3d71d2a964163bf78e25ba93a3817 from './Condition_ccf3d71d2a964163bf78e25ba93a3817.vue'

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
    <span>
        <template v-if="compare(object)">
            <Container_fa6510ef16284343bd891c58b7ad1f20 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
        <template v-else>
            <Condition_ccf3d71d2a964163bf78e25ba93a3817 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
    </span>
</template>