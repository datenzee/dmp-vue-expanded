<script setup>
import Content_daf7b8f83bf842aab7d75d64eefbfd93 from './Content_daf7b8f83bf842aab7d75d64eefbfd93.vue'

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
        <Content_daf7b8f83bf842aab7d75d64eefbfd93 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>