<script setup lang="ts">
definePageMeta({ layout: "test" });

const route = useRoute();

console.log("page", route.params.id);
</script>

<template>
    <div>
        {{ route.params.id }}
    </div>
</template>
