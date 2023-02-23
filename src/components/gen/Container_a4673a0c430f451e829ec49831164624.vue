<script setup>
import Strong_b90843dd8bff44a7903a34e8520ac750 from './Strong_b90843dd8bff44a7903a34e8520ac750.vue'
import Content_ac627b27aaf846f289a4f167b95b5337 from './Content_ac627b27aaf846f289a4f167b95b5337.vue'

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
        <Strong_b90843dd8bff44a7903a34e8520ac750 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_ac627b27aaf846f289a4f167b95b5337 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>