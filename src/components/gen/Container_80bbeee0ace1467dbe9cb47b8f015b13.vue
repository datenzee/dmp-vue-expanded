<script setup>
import Strong_77669e2e87744f9bbc8142b0b4c6dcf5 from './Strong_77669e2e87744f9bbc8142b0b4c6dcf5.vue'
import URL_2c561bbd97b74ea99ba38bfb17275fb2 from './URL_2c561bbd97b74ea99ba38bfb17275fb2.vue'

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
        <Strong_77669e2e87744f9bbc8142b0b4c6dcf5 :graph="graph" :depth="depth + 1" :object="object" />
        <URL_2c561bbd97b74ea99ba38bfb17275fb2 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>