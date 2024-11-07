<script setup>
const result = await fetch('/api/img');
console.log(result);
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
