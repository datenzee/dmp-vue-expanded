<script setup>
import Content_9372b4a12e9e47b69aaa91c9da6ece38 from './Content_9372b4a12e9e47b69aaa91c9da6ece38.vue'

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
        <Content_9372b4a12e9e47b69aaa91c9da6ece38 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>