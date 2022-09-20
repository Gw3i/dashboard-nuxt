<template>
  <div>
    <div class="d-flex">
      <Nav />
      <div class="d-flex flex-column w-100">
        <header
          class="d-flex p-2 mb-5 w-100 h-auto justify-content-between align-items-center border-bottom"
        >
          <h1>Dashboard</h1>
          <button class="btn btn-primary" @click="hello">Create Job</button>
        </header>

        <main class="d-flex justify-content-center">
          <Job />
        </main>
      </div>
    </div>
  </div>
</template>

<script setup>
import Nav from './Nav.vue'
import Job from './Job.vue'
function hello() {
  alert('Hello!')
}
</script>

<style></style>
