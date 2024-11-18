<template>
  <div>
    <NuxtRouteAnnouncer />
    {{app.appName}}
  </div>
</template>

<script setup>
const app = useAppStore()
</script>
