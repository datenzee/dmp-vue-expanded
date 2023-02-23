<script setup>
import Content_d3198379dcfc4e34b6dbfb11f9ab8219 from './Content_d3198379dcfc4e34b6dbfb11f9ab8219.vue'

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
        <Content_d3198379dcfc4e34b6dbfb11f9ab8219 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>