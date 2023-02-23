<script setup>
import Content_0ed11fac5e18452db71ff7aa897b0842 from './Content_0ed11fac5e18452db71ff7aa897b0842.vue'

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
        <Content_0ed11fac5e18452db71ff7aa897b0842 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>