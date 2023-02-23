<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_d7c938c1a33f4821b0f9f443c5068ce6 from './Content_d7c938c1a33f4821b0f9f443c5068ce6.vue'

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
        <Content_d7c938c1a33f4821b0f9f443c5068ce6 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>