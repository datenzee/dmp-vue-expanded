<script setup>
import Strong_b369bbac7a7d4ccfa1157df0e5215ea7 from './Strong_b369bbac7a7d4ccfa1157df0e5215ea7.vue'
import Strong_eecd56e5eea94d9da5640eb62ecc4c42 from './Strong_eecd56e5eea94d9da5640eb62ecc4c42.vue'
import Content_98491d0069124eeb9297cd502e7e1864 from './Content_98491d0069124eeb9297cd502e7e1864.vue'
import Email_e4f226d9b08049e79662ffe984ce6b99 from './Email_e4f226d9b08049e79662ffe984ce6b99.vue'
import Content_fe7f73db521b49f08b451a410c3dc4b3 from './Content_fe7f73db521b49f08b451a410c3dc4b3.vue'
import Emphasis_cdeeec122ab546ff9789517e5a181aca from './Emphasis_cdeeec122ab546ff9789517e5a181aca.vue'

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
        <Strong_b369bbac7a7d4ccfa1157df0e5215ea7 :graph="graph" :depth="depth + 1" :object="object" />
        <Strong_eecd56e5eea94d9da5640eb62ecc4c42 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_98491d0069124eeb9297cd502e7e1864 :graph="graph" :depth="depth + 1" :object="object" />
        <Email_e4f226d9b08049e79662ffe984ce6b99 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_fe7f73db521b49f08b451a410c3dc4b3 :graph="graph" :depth="depth + 1" :object="object" />
        <Emphasis_cdeeec122ab546ff9789517e5a181aca :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>