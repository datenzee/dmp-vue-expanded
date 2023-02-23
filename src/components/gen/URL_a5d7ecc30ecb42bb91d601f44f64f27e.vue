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


const predicate = $rdf.sym('https://w3id.org/dcso/ns/core#licenseRef')


// <custom-code>
// </custom-code>
</script>
<template>
    <a :href="graph?.match(object, predicate)[0]?.object.value" target="_blank">
        {{ graph?.match(object, predicate)[0]?.object.value }}
    </a>
</template>