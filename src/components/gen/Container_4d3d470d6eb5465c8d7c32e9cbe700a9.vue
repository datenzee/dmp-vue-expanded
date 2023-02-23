<script setup>
import Strong_74b4557f61744f8a994679ebf56ca07b from './Strong_74b4557f61744f8a994679ebf56ca07b.vue'
import Date_9fb802599d6c4f258ff7845cf74f6b00 from './Date_9fb802599d6c4f258ff7845cf74f6b00.vue'

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
        <Strong_74b4557f61744f8a994679ebf56ca07b :graph="graph" :depth="depth + 1" :object="object" />
        <Date_9fb802599d6c4f258ff7845cf74f6b00 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>