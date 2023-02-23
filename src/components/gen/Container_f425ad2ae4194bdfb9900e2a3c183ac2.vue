<script setup>
import Content_cc8ab42c377a43deaf5d081645d20b73 from './Content_cc8ab42c377a43deaf5d081645d20b73.vue'
import Container_c14c0084a8eb4f8aa4fcf87f449e0586 from './Container_c14c0084a8eb4f8aa4fcf87f449e0586.vue'
import Container_707a904048df413682fc001bf564b02a from './Container_707a904048df413682fc001bf564b02a.vue'
import Container_008ff9dfe1a14e3b9d9961ae2db3a376 from './Container_008ff9dfe1a14e3b9d9961ae2db3a376.vue'
import Container_80bbeee0ace1467dbe9cb47b8f015b13 from './Container_80bbeee0ace1467dbe9cb47b8f015b13.vue'
import Container_de4ce79f01fa489285f500abca77da47 from './Container_de4ce79f01fa489285f500abca77da47.vue'
import Container_4d281b89d2894a68a95bc3ea37de7cf3 from './Container_4d281b89d2894a68a95bc3ea37de7cf3.vue'
import DataComponent_3bad75b807de47758aa10723c7376654 from './DataComponent_3bad75b807de47758aa10723c7376654.vue'

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
        <Content_cc8ab42c377a43deaf5d081645d20b73 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_c14c0084a8eb4f8aa4fcf87f449e0586 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_707a904048df413682fc001bf564b02a :graph="graph" :depth="depth + 1" :object="object" />
        <Container_008ff9dfe1a14e3b9d9961ae2db3a376 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_80bbeee0ace1467dbe9cb47b8f015b13 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_de4ce79f01fa489285f500abca77da47 :graph="graph" :depth="depth + 1" :object="object" />
        <Container_4d281b89d2894a68a95bc3ea37de7cf3 :graph="graph" :depth="depth + 1" :object="object" />
        <DataComponent_3bad75b807de47758aa10723c7376654 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>