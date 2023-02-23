<script setup>
import Heading_3b74e2c24e144337b415653820232810 from './Heading_3b74e2c24e144337b415653820232810.vue'
import Content_9213b15a78314553b2b34ccc43b41046 from './Content_9213b15a78314553b2b34ccc43b41046.vue'
import DataComponent_830cb055012b47eea65cd81ffdc68eff from './DataComponent_830cb055012b47eea65cd81ffdc68eff.vue'

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
        <Heading_3b74e2c24e144337b415653820232810 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_9213b15a78314553b2b34ccc43b41046 :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_830cb055012b47eea65cd81ffdc68eff :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>