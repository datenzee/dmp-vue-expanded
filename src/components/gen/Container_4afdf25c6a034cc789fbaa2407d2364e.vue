<script setup>
import Strong_2adb8505efe246999ad8189bcffdf85c from './Strong_2adb8505efe246999ad8189bcffdf85c.vue'
import Content_15f43856582c4adb91bff9fb66c35361 from './Content_15f43856582c4adb91bff9fb66c35361.vue'

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
        <Strong_2adb8505efe246999ad8189bcffdf85c :graph="graph" :depth="depth + 1" :object="object" />
        <Content_15f43856582c4adb91bff9fb66c35361 :graph="graph" :depth="depth + 1" :object="object" />
        
    </div>
</template>