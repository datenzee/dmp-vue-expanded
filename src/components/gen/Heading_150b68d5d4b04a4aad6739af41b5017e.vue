<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_f4ae2b7e89f24371ae2273cbff273a21 from './Content_f4ae2b7e89f24371ae2273cbff273a21.vue'

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
        <Content_f4ae2b7e89f24371ae2273cbff273a21 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>