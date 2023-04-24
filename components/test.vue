<script setup lang="ts">
const route = useRoute();

console.log("component", route.params.id);
</script>

<template>
    <div>
        {{ route.params.id }}
    </div>
</template>
