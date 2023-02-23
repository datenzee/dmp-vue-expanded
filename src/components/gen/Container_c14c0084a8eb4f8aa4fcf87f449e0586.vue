<script setup>
import Strong_f3e5c189565a4cb7b529969c9a4642cf from './Strong_f3e5c189565a4cb7b529969c9a4642cf.vue'
import Content_cd7da1cfb89d4aa2a1d78fd9a8ee17eb from './Content_cd7da1cfb89d4aa2a1d78fd9a8ee17eb.vue'

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
        <Strong_f3e5c189565a4cb7b529969c9a4642cf :graph="graph" :depth="depth + 1" :object="object" />
        <Content_cd7da1cfb89d4aa2a1d78fd9a8ee17eb :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>