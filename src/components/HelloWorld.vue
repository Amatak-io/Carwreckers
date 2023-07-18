<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
      Price Guarantee
  </div>
  <nav class="breadcrumb" aria-label="breadcrumbs">
  <ul>
    <li><a href="#">Services</a></li>
    <li><a href="#">Free Quote</a></li>
    <li><a href="#">Car Scrapping</a></li>
    <li><a href="#">Unwant Remove Car</a></li>
    <li><a href="#">Cash For Car</a></li>
  </ul>
</nav>

</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
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
