<script setup>
import Heading_131040725bf54e638b7aed3616435b37 from './Heading_131040725bf54e638b7aed3616435b37.vue'
import Strong_2012e2bd43fa4e5795afbfbf061b8222 from './Strong_2012e2bd43fa4e5795afbfbf061b8222.vue'
import Content_7a42ee6dc8394c4d87a14e5573bbc27c from './Content_7a42ee6dc8394c4d87a14e5573bbc27c.vue'
import Container_eea9aa589a234ef9a472f1abf0f2375e from './Container_eea9aa589a234ef9a472f1abf0f2375e.vue'
import Container_81cdb09a6cb14fae85692347c7f09a9f from './Container_81cdb09a6cb14fae85692347c7f09a9f.vue'
import Container_e19937d5368a4661b644fac360d8e650 from './Container_e19937d5368a4661b644fac360d8e650.vue'
import Container_8c1b830504a147349277c2d53a9bd342 from './Container_8c1b830504a147349277c2d53a9bd342.vue'

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
        <Heading_131040725bf54e638b7aed3616435b37 :graph="graph" :depth="depth + 1" :object="object" />
        <Strong_2012e2bd43fa4e5795afbfbf061b8222 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_7a42ee6dc8394c4d87a14e5573bbc27c :graph="graph" :depth="depth + 1" :object="object" />
        <Container_eea9aa589a234ef9a472f1abf0f2375e :graph="graph" :depth="depth + 1" :object="object" />
        <Container_81cdb09a6cb14fae85692347c7f09a9f :graph="graph" :depth="depth + 1" :object="object" />
        <Container_e19937d5368a4661b644fac360d8e650 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_8c1b830504a147349277c2d53a9bd342 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>