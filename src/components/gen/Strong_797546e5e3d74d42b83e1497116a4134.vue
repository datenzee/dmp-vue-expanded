<script setup>
import Content_7fae5073994b4b38813ad43588df4cd8 from './Content_7fae5073994b4b38813ad43588df4cd8.vue'

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
        <Content_7fae5073994b4b38813ad43588df4cd8 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>