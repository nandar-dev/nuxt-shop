<template>
  <h1>Products details for {{ id }}</h1>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta({
  layout: "products",
});
</script>
