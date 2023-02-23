<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_763ddc7ed45b4c9bbb14d7c399926ce6 from './Content_763ddc7ed45b4c9bbb14d7c399926ce6.vue'

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
        <Content_763ddc7ed45b4c9bbb14d7c399926ce6 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>