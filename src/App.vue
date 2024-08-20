<template>
  <div class="container">
    <header>
      <Navigation></Navigation>
    </header>
    <body class="body">
      <RouterView />
    </body>
  </div>
</template>
<script setup>
import Navigation from "./components/Navigation.vue";
</script>

<style scoped>
.container {
  min-height: 100vh;
  min-width: 100vw;
  margin: -8px;
}
.body {
  padding-top: 70px;
}
</style>
