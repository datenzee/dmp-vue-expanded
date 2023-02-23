<script setup>
import Strong_797546e5e3d74d42b83e1497116a4134 from './Strong_797546e5e3d74d42b83e1497116a4134.vue'
import Content_99eaa0796bde4cac825c76d04ea12942 from './Content_99eaa0796bde4cac825c76d04ea12942.vue'

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
        <Strong_797546e5e3d74d42b83e1497116a4134 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_99eaa0796bde4cac825c76d04ea12942 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>