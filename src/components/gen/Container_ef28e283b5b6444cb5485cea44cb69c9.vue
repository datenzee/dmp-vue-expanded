<script setup>
import Strong_45c3aa95c077442eaa531a127dabb47c from './Strong_45c3aa95c077442eaa531a127dabb47c.vue'
import Strong_8d7c885784f4422eb3e4b9ebd7cde48f from './Strong_8d7c885784f4422eb3e4b9ebd7cde48f.vue'
import Content_70da1a75095f427d83e15fab492f7ef5 from './Content_70da1a75095f427d83e15fab492f7ef5.vue'
import Email_7a191f7ac53c4b69aab039206d0761b4 from './Email_7a191f7ac53c4b69aab039206d0761b4.vue'
import Content_da407200d8274f12afb294ecaacfb3e7 from './Content_da407200d8274f12afb294ecaacfb3e7.vue'

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
        <Strong_45c3aa95c077442eaa531a127dabb47c :graph="graph" :depth="depth + 1" :object="object" />
        <Strong_8d7c885784f4422eb3e4b9ebd7cde48f :graph="graph" :depth="depth + 1" :object="object" />
        <Content_70da1a75095f427d83e15fab492f7ef5 :graph="graph" :depth="depth + 1" :object="object" />
        <Email_7a191f7ac53c4b69aab039206d0761b4 :graph="graph" :depth="depth + 1" :object="object" />
        <Content_da407200d8274f12afb294ecaacfb3e7 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>