<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_b9137cf67b69410c902a0a6432df44c5 from './Content_b9137cf67b69410c902a0a6432df44c5.vue'

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
    <Heading :depth="depth">
        <Content_b9137cf67b69410c902a0a6432df44c5 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>