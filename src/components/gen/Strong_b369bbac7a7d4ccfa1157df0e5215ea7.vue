<script setup>
import Content_ea3e6e206d2f40a6818fa0b613efc7ea from './Content_ea3e6e206d2f40a6818fa0b613efc7ea.vue'

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
        <Content_ea3e6e206d2f40a6818fa0b613efc7ea :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>