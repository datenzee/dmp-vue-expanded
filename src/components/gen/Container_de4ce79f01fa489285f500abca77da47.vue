<script setup>
import Strong_8a137db512ad4b0283a6f81e83cda5c5 from './Strong_8a137db512ad4b0283a6f81e83cda5c5.vue'
import Date_d9bd657df775410c949a8387291fb501 from './Date_d9bd657df775410c949a8387291fb501.vue'

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
        <Strong_8a137db512ad4b0283a6f81e83cda5c5 :graph="graph" :depth="depth + 1" :object="object" />
        <Date_d9bd657df775410c949a8387291fb501 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>