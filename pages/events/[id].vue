<script>
const route = useRoute();
const nuxtApp = useNuxtApp();

console.log(route.params);
</script>

<template>
    <div>event id: {{ $route.params.id }}</div>
</template>
