<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_0014cf9f6e71429fa41ab1998d28f572 from './Content_0014cf9f6e71429fa41ab1998d28f572.vue'

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
        <Content_0014cf9f6e71429fa41ab1998d28f572 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>