<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header class="header">
    <span class="logo">PHYSIOHABITS</span> 

    <div class="wrapper">
      <HelloWorld/>
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
    <footer>
©2023, Physiobabits
</footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  text-align:center;
}
  header {
    align-items:center;
  }
@media (min-width: 1024px) {
  header {
    display: flex;
    flex-direction: column;    
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }



  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
<style lang="scss">
@import "./assets/style.scss";
</style>
