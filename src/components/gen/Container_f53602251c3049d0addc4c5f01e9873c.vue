<script setup>
import Strong_d6b7943f39e74cbba8ab545b8c4ca3fc from './Strong_d6b7943f39e74cbba8ab545b8c4ca3fc.vue'
import Date_bd8934776a594bffbab88523e0a4e07c from './Date_bd8934776a594bffbab88523e0a4e07c.vue'

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
        <Strong_d6b7943f39e74cbba8ab545b8c4ca3fc :graph="graph" :depth="depth + 1" :object="object" />
        <Date_bd8934776a594bffbab88523e0a4e07c :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>