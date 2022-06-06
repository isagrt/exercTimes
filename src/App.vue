<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import FooterComp from "@/components/template/FooterComp.vue";
</script>
<template>
  <HeaderComp />
  <main>
    <RouterView />
  </main>
  <FooterComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: calc(100-1.5rem);
  margin: 0 auto;
  font-weight: normal;
  height: 100vh;
}
a {
  color: inherit;
  text-decoration: none;
}

footer {
  background-color: rgb(188, 131, 226);
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
  justify-content: space-between;
}

main {
  min-height: 70%;
}
</style>
