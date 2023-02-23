<script setup>
import Heading from '@/components/vo/Heading.vue'
import Content_02348a6ee70f40908adbd436307ba360 from './Content_02348a6ee70f40908adbd436307ba360.vue'

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
        <Content_02348a6ee70f40908adbd436307ba360 :graph="graph" :depth="depth + 1" :object="object" />
        
    </Heading>
</template>