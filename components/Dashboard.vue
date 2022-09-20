<template>
  <div>
    <header>
      <h1>Dashboard</h1>
      <button @click="hello">Create Job</button>
    </header>
    <main></main>
  </div>
</template>

<script setup>
function hello() {
  alert('Hello!')
}
</script>

<style></style>
