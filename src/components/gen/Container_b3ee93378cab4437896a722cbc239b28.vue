<script setup>
import Content_c6f7ea9473d2489f9ba9645eca97356c from './Content_c6f7ea9473d2489f9ba9645eca97356c.vue'

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
        <Content_c6f7ea9473d2489f9ba9645eca97356c :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>