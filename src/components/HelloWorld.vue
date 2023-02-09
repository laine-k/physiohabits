<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1>Up to 70% quit their home exercises given by physio</h1>
    <h3>
    Physiobabits is here to assist with healthy habit building through ideas and research
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
  font-family: 'Playfair Display', Georgia, serif;
}

.greetings {
padding: 2em;
}
@media (min-width: 1024px) {
  .greetings {
  padding: 3em;
  }
}

</style>
