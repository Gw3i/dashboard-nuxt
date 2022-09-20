<template>
  <div>
    <div class="d-flex">
      <Nav />
      <header>
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
