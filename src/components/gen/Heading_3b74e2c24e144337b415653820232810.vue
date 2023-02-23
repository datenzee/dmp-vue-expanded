<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_dab956d009514e0bbc69a47afdc92099 from './Content_dab956d009514e0bbc69a47afdc92099.vue'

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
        <Content_dab956d009514e0bbc69a47afdc92099 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>