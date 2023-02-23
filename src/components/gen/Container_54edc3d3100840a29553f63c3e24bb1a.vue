<script setup>
import Heading_1c650821dbd245eb854046e0cb7bc38f from './Heading_1c650821dbd245eb854046e0cb7bc38f.vue'
import Container_f425ad2ae4194bdfb9900e2a3c183ac2 from './Container_f425ad2ae4194bdfb9900e2a3c183ac2.vue'

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
        <Heading_1c650821dbd245eb854046e0cb7bc38f :graph="graph" :depth="depth + 1" :object="object" />
        <Container_f425ad2ae4194bdfb9900e2a3c183ac2 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>