<script setup>
import Strong_f5c143068d0949fbb6d75aa0db6ea6be from './Strong_f5c143068d0949fbb6d75aa0db6ea6be.vue'
import Content_787c8ee3dd3c4b858a20c98cd6776c96 from './Content_787c8ee3dd3c4b858a20c98cd6776c96.vue'

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
        <Strong_f5c143068d0949fbb6d75aa0db6ea6be :graph="graph" :depth="depth + 1" :object="object" />
        <Content_787c8ee3dd3c4b858a20c98cd6776c96 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>