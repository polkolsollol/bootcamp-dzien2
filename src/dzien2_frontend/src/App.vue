<script setup>
import Blog from './components/Blog.vue';

</script>

<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    <h1 class="text-blue-600">Siema?!</h1>
    <form action="#" @submit="handleSubmit">
      <label for="name">Enter your name: &nbsp;</label>
      <input id="name" alt="Name" type="text" />
      <input id="numer" alt="Numer" type="number" />
      <button type="submit">Click Me!</button>
    </form>
    <section id="greeting">{{ greeting }}</section>
    <Blog />
  </main>
</template>