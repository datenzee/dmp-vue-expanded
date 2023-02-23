<script setup>
import Content_c6bded33dedc4951bf2bcd14f53cdfcc from './Content_c6bded33dedc4951bf2bcd14f53cdfcc.vue'

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
    <div>
        <Content_c6bded33dedc4951bf2bcd14f53cdfcc :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>