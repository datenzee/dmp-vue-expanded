<script setup>
import * as $rdf from 'rdflib'
import Container_19bf8099729642f7a866a45be49cdca6 from './Container_19bf8099729642f7a866a45be49cdca6.vue'

import Condition_a58216c8ae944690944da0053f0c902d from './Condition_a58216c8ae944690944da0053f0c902d.vue'

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
            <Container_19bf8099729642f7a866a45be49cdca6 :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
        <template v-else>
            <Condition_a58216c8ae944690944da0053f0c902d :graph="graph" :depth="depth + 1" :object="object" />
            
        </template>
    </span>
</template>