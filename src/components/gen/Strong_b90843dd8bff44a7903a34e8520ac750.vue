<script setup>
import Content_7a37d97c7b1247299b0e2065b276be97 from './Content_7a37d97c7b1247299b0e2065b276be97.vue'

// <custom-imports>
// </custom-imports>


const props = defineProps([
    'graph',
    'depth',
    'object',
    // <custom-props>
    // </custom-props>
])

// <custom-code>
// </custom-code>
</script>
<template>
    <strong>
        <Content_7a37d97c7b1247299b0e2065b276be97 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>