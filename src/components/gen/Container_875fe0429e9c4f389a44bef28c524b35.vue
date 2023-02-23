<script setup>
import Content_3ab59846143543fd829137307ed857ad from './Content_3ab59846143543fd829137307ed857ad.vue'

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
        <Content_3ab59846143543fd829137307ed857ad :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>