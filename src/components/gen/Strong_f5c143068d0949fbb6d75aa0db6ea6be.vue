<script setup>
import Content_089a1731db2f44679042657f30ea6001 from './Content_089a1731db2f44679042657f30ea6001.vue'

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
        <Content_089a1731db2f44679042657f30ea6001 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>