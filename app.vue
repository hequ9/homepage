<script lang="ts" setup>
import 'assets/style/transition.scss'
import '@unocss/reset/sanitize/sanitize.css'
</script>

<template>
  <NuxtPage />
</template>

<style lang="scss">
html {
  font-family: 'Roboto', 'Noto Sans SC';
  color:#333;
}
body {
  @apply bg-gradient-to-r from-#111111 to-#001E36 min-h-100vh;
}
</style>
