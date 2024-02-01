<template>
  <div class="h-dvh w-dvw grid grid-cols-1 content-center">
    <div class="mx-auto p-10 w-fit bg-teal-200 rounded-lg shadow-lg">
      <slot />
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style>

h2 {
  font-size: 30px;
  margin-bottom: 15px;
  padding-left: 5px;
}

form input {
  padding: 4px 12px;
  margin: 5px 0;
  border: 1px rgba(189, 189, 189, 0.64) solid;
  border-radius: 7px;
}

form button[type="submit"] {
  border-radius: 6px;
  background-color: rgb(5, 150, 105);
  color: white;
  font-weight: bold;
  margin: 10px 0 0;
  padding: 4px 0;
  width: 100%;
  transition: background-color 0.3s;
  transition-timing-function: ease;
}

button[type="submit"]:hover {
  background-color: rgb(36, 50, 45);
}
</style>
