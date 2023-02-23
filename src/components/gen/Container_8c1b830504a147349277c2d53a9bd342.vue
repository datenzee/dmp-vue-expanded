<script setup>
import Heading_150b68d5d4b04a4aad6739af41b5017e from './Heading_150b68d5d4b04a4aad6739af41b5017e.vue'
import Content_a1ba72308a6149ceb90e383854a8e85a from './Content_a1ba72308a6149ceb90e383854a8e85a.vue'
import DataComponent_414bea604d0e4ad689159e1c1a3a5108 from './DataComponent_414bea604d0e4ad689159e1c1a3a5108.vue'

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
        <Heading_150b68d5d4b04a4aad6739af41b5017e :graph="graph" :depth="depth + 1" :object="object" />
        <Content_a1ba72308a6149ceb90e383854a8e85a :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_414bea604d0e4ad689159e1c1a3a5108 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>