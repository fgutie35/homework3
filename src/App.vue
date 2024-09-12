<script setup>
  import {ref} from 'vue'

  const name = ref('')

</script>

<template>

<main class="app">

  <selection class="greeting">
    <h2 class="title">
      Welcome back, <input type="text" placeholder="Enter Name" v-model="name">
    </h2>

  </selection>

  <section class="create todo">


  </section>

  <selection class="todo-list">

  </selection>


</main>

</template>


