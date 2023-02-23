<script setup>
import Heading_5344f21d50264749ab23273802981e40 from './Heading_5344f21d50264749ab23273802981e40.vue'
import Content_95e0d89319294ad494b6ab44312e68d8 from './Content_95e0d89319294ad494b6ab44312e68d8.vue'
import DataComponent_ac3e33ef76624659a7f8454a6a6b18fd from './DataComponent_ac3e33ef76624659a7f8454a6a6b18fd.vue'

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
        <Heading_5344f21d50264749ab23273802981e40 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_95e0d89319294ad494b6ab44312e68d8 :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_ac3e33ef76624659a7f8454a6a6b18fd :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>