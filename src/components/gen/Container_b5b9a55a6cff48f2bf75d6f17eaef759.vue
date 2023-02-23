<script setup>
import Content_4756b3580b8b494d8bde114929197f4c from './Content_4756b3580b8b494d8bde114929197f4c.vue'

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
        <Content_4756b3580b8b494d8bde114929197f4c :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>