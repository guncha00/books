<template>
  <div class="bg-bg">
    <header>
      <h1>Index</h1>
      <!-- <NuxtLayout name="default"></NuxtLayout> -->
    </header>

    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi
      similique nemo unde delectus fugit accusantium.
    </p>
    <div class="checkList">
      <ul>
        <li><NuxtLink to="/contact">Homepage</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
      </ul>
    </div>
    <!-- 
    <NuxtLayout name="footer"> </NuxtLayout> -->
  </div>
</template>

<script setup></script>

<style scoped>
.checkList {
  display: flexbox;
  justify-content: space-between;
}
</style>
