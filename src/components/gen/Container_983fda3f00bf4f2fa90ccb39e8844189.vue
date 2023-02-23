<script setup>
import Strong_ffa14e5918654318aa66dd9bb25230ea from './Strong_ffa14e5918654318aa66dd9bb25230ea.vue'
import Date_5ec6ab60aa72441189b974b7d3c8d2c9 from './Date_5ec6ab60aa72441189b974b7d3c8d2c9.vue'

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
        <Strong_ffa14e5918654318aa66dd9bb25230ea :graph="graph" :depth="depth + 1" :object="object" />
        <Date_5ec6ab60aa72441189b974b7d3c8d2c9 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>