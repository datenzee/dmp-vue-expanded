<script setup>
import Content_ffd1e785b88a4a62a6c8eea7639d04b3 from './Content_ffd1e785b88a4a62a6c8eea7639d04b3.vue'

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
        <Content_ffd1e785b88a4a62a6c8eea7639d04b3 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>