<script setup>
import Logo from "./components/Logo.vue";
import Info from "./components/Info.vue";
</script>

<template>
  <main>
    <Logo />
    <Info />
  </main>
</template>

<style scoped>
main {
  /* width: 90%; */
  /* height: 100vh; */
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  flex-direction: column-reverse;
  align-items: center;
  padding: 40px;
}

@media (min-width: 1024px) {
  main {
    width: 90%;
    height: 100vh;
    flex-direction: row;
  }
}
</style>
