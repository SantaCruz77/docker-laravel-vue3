<script setup>
const props = defineProps({
    link: String,
    name: String,
});
</script>

<template>
    <v-btn variant="outlined" :to="Link">{{ name }}</v-btn>
</template>
