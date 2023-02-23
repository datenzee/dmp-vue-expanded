<script setup>
import Content_91f1f08fefab4d09b1f48c80d1b090c0 from './Content_91f1f08fefab4d09b1f48c80d1b090c0.vue'

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
        <Content_91f1f08fefab4d09b1f48c80d1b090c0 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>