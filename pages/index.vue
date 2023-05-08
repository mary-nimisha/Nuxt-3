<template>
<h2>This is our landing page</h2>
  <nav>
    <NuxtLink to="/welcome" class="home-link">
      <i class="fas fa-home"></i>
    Go to Welcome Page
    </NuxtLink>
  </nav>
 
</template>

<script setup>
const runtimeConfig = useRuntimeConfig()
const appConfig = useAppConfig()
</script>
