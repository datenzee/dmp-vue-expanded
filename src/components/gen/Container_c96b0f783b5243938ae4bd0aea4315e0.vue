<script setup>
import Heading_21611d8183df4d7780be83ad39275339 from './Heading_21611d8183df4d7780be83ad39275339.vue'
import Content_60e5a94bc7b34819b00024876fe0b5df from './Content_60e5a94bc7b34819b00024876fe0b5df.vue'
import Container_a4673a0c430f451e829ec49831164624 from './Container_a4673a0c430f451e829ec49831164624.vue'
import Container_4d3d470d6eb5465c8d7c32e9cbe700a9 from './Container_4d3d470d6eb5465c8d7c32e9cbe700a9.vue'
import Container_4afdf25c6a034cc789fbaa2407d2364e from './Container_4afdf25c6a034cc789fbaa2407d2364e.vue'
import Condition_1a4d81c212cc47d4a96f499a0a11529b from './Condition_1a4d81c212cc47d4a96f499a0a11529b.vue'
import Condition_f4aaa97c9acc441ab489fc928e0961f0 from './Condition_f4aaa97c9acc441ab489fc928e0961f0.vue'
import Container_fc4bd849b3aa4ad5b3e7e716852a9c9c from './Container_fc4bd849b3aa4ad5b3e7e716852a9c9c.vue'
import Container_d99297ca526f470ba1741b63be2b79a7 from './Container_d99297ca526f470ba1741b63be2b79a7.vue'

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
        <Heading_21611d8183df4d7780be83ad39275339 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_60e5a94bc7b34819b00024876fe0b5df :graph="graph" :depth="depth + 1" :object="object" />
        <Container_a4673a0c430f451e829ec49831164624 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_4d3d470d6eb5465c8d7c32e9cbe700a9 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_4afdf25c6a034cc789fbaa2407d2364e :graph="graph" :depth="depth + 1" :object="object" />
        <Condition_1a4d81c212cc47d4a96f499a0a11529b :graph="graph" :depth="depth + 1" :object="object" />
        <Condition_f4aaa97c9acc441ab489fc928e0961f0 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_fc4bd849b3aa4ad5b3e7e716852a9c9c :graph="graph" :depth="depth + 1" :object="object" />
        <Container_d99297ca526f470ba1741b63be2b79a7 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>