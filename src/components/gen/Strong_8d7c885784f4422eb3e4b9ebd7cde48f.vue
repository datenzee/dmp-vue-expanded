<script setup>
import Content_34a0766e4a8047afa59b0f97bde1273d from './Content_34a0766e4a8047afa59b0f97bde1273d.vue'

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
        <Content_34a0766e4a8047afa59b0f97bde1273d :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>