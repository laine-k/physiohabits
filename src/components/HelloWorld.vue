<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">Up to 70% quit their home exercise program. <br> Does it sound familiar?</h1>
    <h3>
      Non-adherence to home exercise has been shown to be as high as 50-70%.
      <a href="https://www.sciencedirect.com/science/article/pii/S1529943013014745?casa_token=3913WKQJ0c8AAAAA:6d9FpoBmL6wA7KMUnvoP1kRorA7X3Yaa4JbHPCaShJo4fD9_nT6q6dUWa_MzRuZcmDbMf-wh" target="_blank" rel="noopener">Low back pain</a> +
      <a href="https://www.academia.edu/download/55865376/Bassett2003.pdf" target="_blank" rel="noopener">Muskolosceletal conditions</a>.
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
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
