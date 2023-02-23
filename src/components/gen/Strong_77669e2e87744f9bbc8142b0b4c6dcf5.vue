<script setup>
import Content_d5578791229b4639b74cf62c21c505ed from './Content_d5578791229b4639b74cf62c21c505ed.vue'

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
    <strong style="display: block">
        <Content_d5578791229b4639b74cf62c21c505ed :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>