<template>
  <div>
    <header class="shadow-lg">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/" class="font-semibold text-xl">Sahatsawatt_ankt</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/project">Project</NuxtLink></li>
          <li><NuxtLink to="/resume">Resume</NuxtLink></li>
          <li><NuxtLink to="/login">Login</NuxtLink></li>
          <li><NuxtLink to="/register">Register</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <div class="container mx-auto p-4">
      <slot />
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style>
body {
  background-color: white;
}

.router-link-active.router-link-exact-active {
  color: seagreen;
}
h1 {
  font-size: 40px;
}

</style>
