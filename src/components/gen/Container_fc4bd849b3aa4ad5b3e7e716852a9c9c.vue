<script setup>
import Content_645749efa1c7469da6d7fc58eebc1241 from './Content_645749efa1c7469da6d7fc58eebc1241.vue'

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
        <Content_645749efa1c7469da6d7fc58eebc1241 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>