<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

//const count = ref(0)
</script>

<template>
  <nav class="bar">
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</template>
  


<style scoped>
nav {
  background-color: #333;
  overflow: hidden;
  display: flex;
  justify-content: flex-end;
  padding: 14px 16px;
  position: absolute;
  left: 0%;
  top: 0%;
}

nav ul {
  list-style-type:    none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  display: block;
  color: rgb(0, 0, 0);
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}



nav ul li a:hover {
  background-color: #615f5f;
}
</style>
