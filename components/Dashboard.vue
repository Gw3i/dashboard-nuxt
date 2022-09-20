<template>
  <div>
    <div class="d-flex">
      <Nav />
      <header class="d-flex p-2 w-100 h-25 justify-content-between">
        <h1>Dashboard</h1>
        <button @click="hello">Create Job</button>
      </header>
    </div>
    <main></main>
  </div>
</template>

<script setup>
import Nav from './Nav.vue'
function hello() {
  alert('Hello!')
}
</script>

<style></style>
