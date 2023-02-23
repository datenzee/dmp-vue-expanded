<script setup>
import * as $rdf from 'rdflib'
// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])


const predicate = $rdf.sym('http://xmlns.com/foaf/0.1/name')


// <custom-code>
// </custom-code>
</script>
<template>
    <span>{{ graph?.match(object, predicate)[0]?.object.value }}</span>
</template>