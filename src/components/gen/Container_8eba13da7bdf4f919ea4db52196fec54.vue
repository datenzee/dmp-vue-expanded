<script setup>
import Content_f919c258e02b40a784e520118f4b07b5 from './Content_f919c258e02b40a784e520118f4b07b5.vue'

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
    <div>
        <Content_f919c258e02b40a784e520118f4b07b5 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>