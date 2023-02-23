<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_11f952326f8c4235b1cdd5d5598b508c from './Content_11f952326f8c4235b1cdd5d5598b508c.vue'

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
        <Content_11f952326f8c4235b1cdd5d5598b508c :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>