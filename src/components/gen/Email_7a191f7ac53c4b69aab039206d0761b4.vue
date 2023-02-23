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


const predicate = $rdf.sym('http://xmlns.com/foaf/0.1/mbox')


// <custom-code>
// </custom-code>
</script>
<template>
    <a :href="`mailto:${graph?.match(object, predicate)[0]?.object.value}`" >{{ graph?.match(object, predicate)[0]?.object.value }}</a>
</template>