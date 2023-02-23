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


const predicate = $rdf.sym('http://www.w3.org/ns/dcat#keyword')


// <custom-code>
// </custom-code>
</script>
<template>
    <span>{{ graph?.match(object, predicate)[0]?.object.value }}</span>
</template>