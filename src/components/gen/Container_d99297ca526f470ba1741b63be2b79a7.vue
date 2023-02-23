<script setup>
import Heading_7aa83e9f495449a3ac18590aae9832d9 from './Heading_7aa83e9f495449a3ac18590aae9832d9.vue'
import Container_875fe0429e9c4f389a44bef28c524b35 from './Container_875fe0429e9c4f389a44bef28c524b35.vue'
import DataComponent_8be7ac40b04941b2978eb6b31523b820 from './DataComponent_8be7ac40b04941b2978eb6b31523b820.vue'

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
        <Heading_7aa83e9f495449a3ac18590aae9832d9 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_875fe0429e9c4f389a44bef28c524b35 :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_8be7ac40b04941b2978eb6b31523b820 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>