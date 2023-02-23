<script setup>
import * as $rdf from 'rdflib'
import moment from 'moment'
// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])


const predicate = $rdf.sym('http://purl.org/dc/terms/issued')


const format = (value) => moment(value).format('MMMM Do YYYY')
// <custom-code>
// </custom-code>
</script>
<template>
    <span>{{ format(graph?.match(object, predicate)[0]?.object.value) }}</span>
</template>