<script setup>
import Content_cb34ff46bfa5497aac0d2ba7cdbba561 from './Content_cb34ff46bfa5497aac0d2ba7cdbba561.vue'

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
        <Content_cb34ff46bfa5497aac0d2ba7cdbba561 :graph="graph" :depth="depth + 1" :object="object" />
        
    </strong>
</template>