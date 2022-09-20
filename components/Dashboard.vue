<template>
  <div>
    <header>
      <h1>Dashboard</h1>
      <button @click="hello">Create Job</button>
    </header>
    <nav
      class="d-flex flex-column flex-shrink-0 p-3 text-white bg-dark"
      style="width: 280px"
    >
      <ul class="nav nav-pills flex-column mb-auto">
        <li class="nav-item">
          <NuxtLink class="nav-link text-white" to="/">Dashboard</NuxtLink>
        </li>
        <li class="nav-item">
          <button class="nav-link text-white">Create Job</button>
        </li>
        <li class="nav-item">
          <button class="nav-link text-white">Edit Job</button>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link text-white" to="/statistics"
            >Statistics</NuxtLink
          >
        </li>
        <li class="nav-item">
          <button class="nav-link text-white">Alerts</button>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link text-white" to="/logs">Logs</NuxtLink>
        </li>
      </ul>
    </nav>
    <main></main>
  </div>
</template>

<script setup>
function hello() {
  alert('Hello!')
}
</script>

<style></style>
