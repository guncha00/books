<script setup>
definePageMeta({
  layout: false,
});
</script>

<template>
  <div>
    <h1>Contact</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores,
      nihil.
    </p>
    <div class="bg-bg">
      <span><NuxtLink to="/about">Go to about</NuxtLink></span>
    </div>
    <NuxtLayout :name="footer">
      <p>hello it is contact!</p>
      <p>не знаю почему так происходит</p>
    </NuxtLayout>
  </div>
</template>

<style scoped>
h1 {
  color: blue;
}
p {
  color: green;
}
</style>
