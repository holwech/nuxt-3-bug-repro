<script setup lang="ts">
const route = useRoute();

console.log("layout", route.params.id);
</script>

<template>
    <div>
        <test></test>
        <slot></slot>
    </div>
</template>
