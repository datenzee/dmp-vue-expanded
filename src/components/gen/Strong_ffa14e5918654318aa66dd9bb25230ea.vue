<script setup>
import Content_c0c778605cc443c8bb17d36d36466677 from './Content_c0c778605cc443c8bb17d36d36466677.vue'

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
    <strong>
        <Content_c0c778605cc443c8bb17d36d36466677 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>