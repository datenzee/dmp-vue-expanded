<script setup>
import Strong_e6ca4d01f3b34d01bcc134daa904ee6e from './Strong_e6ca4d01f3b34d01bcc134daa904ee6e.vue'
import URL_638e96963e3f4039a3445cd20d2f12d0 from './URL_638e96963e3f4039a3445cd20d2f12d0.vue'

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
        <Strong_e6ca4d01f3b34d01bcc134daa904ee6e :graph="graph" :depth="depth + 1" :object="object" />
        <URL_638e96963e3f4039a3445cd20d2f12d0 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>