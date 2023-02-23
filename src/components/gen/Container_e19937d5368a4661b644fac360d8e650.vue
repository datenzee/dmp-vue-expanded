<script setup>
import Heading_bbca39fe53224d9486646c834d1a1782 from './Heading_bbca39fe53224d9486646c834d1a1782.vue'
import Content_cb970ee3817f4656a36a14237a58c765 from './Content_cb970ee3817f4656a36a14237a58c765.vue'
import DataComponent_eeebae9ee0fc4b32a53d21b13a057259 from './DataComponent_eeebae9ee0fc4b32a53d21b13a057259.vue'

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
        <Heading_bbca39fe53224d9486646c834d1a1782 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_cb970ee3817f4656a36a14237a58c765 :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_eeebae9ee0fc4b32a53d21b13a057259 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>