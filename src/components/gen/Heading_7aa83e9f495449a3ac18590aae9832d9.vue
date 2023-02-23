<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_b71373a2065647b1bf54e8523e7eb62e from './Content_b71373a2065647b1bf54e8523e7eb62e.vue'

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
        <Content_b71373a2065647b1bf54e8523e7eb62e :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>