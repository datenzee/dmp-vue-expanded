<script setup>
import Content_679b413e33704dceb9c233b0ceb502e6 from './Content_679b413e33704dceb9c233b0ceb502e6.vue'
import Date_eb0f4905a6714e6096304d64abcdfc4e from './Date_eb0f4905a6714e6096304d64abcdfc4e.vue'
import Content_3fb7aebe70e140eca4cad97159ad8698 from './Content_3fb7aebe70e140eca4cad97159ad8698.vue'
import URL_a5d7ecc30ecb42bb91d601f44f64f27e from './URL_a5d7ecc30ecb42bb91d601f44f64f27e.vue'
import Content_bc5b8b9c2ad14876bb6cb1b15d1a10df from './Content_bc5b8b9c2ad14876bb6cb1b15d1a10df.vue'

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
        <Content_679b413e33704dceb9c233b0ceb502e6 :graph="graph" :depth="depth + 1" :object="object" />
        <Date_eb0f4905a6714e6096304d64abcdfc4e :graph="graph" :depth="depth + 1" :object="object" />
        <Content_3fb7aebe70e140eca4cad97159ad8698 :graph="graph" :depth="depth + 1" :object="object" />
        <URL_a5d7ecc30ecb42bb91d601f44f64f27e :graph="graph" :depth="depth + 1" :object="object" />
        <Content_bc5b8b9c2ad14876bb6cb1b15d1a10df :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>