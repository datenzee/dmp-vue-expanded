<script setup>
import Content_fcd5d987b389439386592f528871b01b from './Content_fcd5d987b389439386592f528871b01b.vue'

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
        <Content_fcd5d987b389439386592f528871b01b :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>