<template>
  <h1>About</h1>

  <div>
    {{ data }}
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/test",{
    params: {
        name: "test"
    }
});
</script>
