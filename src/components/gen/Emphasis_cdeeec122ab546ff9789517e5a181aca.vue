<script setup>
import Content_6b8cab3c07644a749446b494e4d12d7b from './Content_6b8cab3c07644a749446b494e4d12d7b.vue'

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
    <em>
        <Content_6b8cab3c07644a749446b494e4d12d7b :graph="graph" :depth="depth + 1" :object="object" />
        
    </em>
</template>