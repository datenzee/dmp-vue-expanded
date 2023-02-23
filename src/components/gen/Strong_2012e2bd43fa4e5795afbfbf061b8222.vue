<script setup>
import Content_a44a18916fe04d1eae5446832505ce61 from './Content_a44a18916fe04d1eae5446832505ce61.vue'

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
    <strong style="display: block">
        <Content_a44a18916fe04d1eae5446832505ce61 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>