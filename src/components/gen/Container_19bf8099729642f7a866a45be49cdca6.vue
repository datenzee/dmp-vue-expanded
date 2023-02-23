<script setup>
import Content_ee9958fdca0741db934535839772053e from './Content_ee9958fdca0741db934535839772053e.vue'

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
        <Content_ee9958fdca0741db934535839772053e :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>