<script setup>
import Heading_1300e3ef099d4c6eb1ea2e4e2eb39d28 from './Heading_1300e3ef099d4c6eb1ea2e4e2eb39d28.vue'
import Content_625e299f26e64dfabb575c4899bd45a8 from './Content_625e299f26e64dfabb575c4899bd45a8.vue'
import Container_f53602251c3049d0addc4c5f01e9873c from './Container_f53602251c3049d0addc4c5f01e9873c.vue'
import Container_983fda3f00bf4f2fa90ccb39e8844189 from './Container_983fda3f00bf4f2fa90ccb39e8844189.vue'

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
        <Heading_1300e3ef099d4c6eb1ea2e4e2eb39d28 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_625e299f26e64dfabb575c4899bd45a8 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_f53602251c3049d0addc4c5f01e9873c :graph="graph" :depth="depth + 1" :object="object" />
        <Container_983fda3f00bf4f2fa90ccb39e8844189 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>