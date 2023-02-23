<script setup>
import Content_5b0a10ff7cd94dbaaec4fc699e5e7e11 from './Content_5b0a10ff7cd94dbaaec4fc699e5e7e11.vue'

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
        <Content_5b0a10ff7cd94dbaaec4fc699e5e7e11 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>