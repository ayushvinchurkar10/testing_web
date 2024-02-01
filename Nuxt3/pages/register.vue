<template>
  <div>
    <h1>Register</h1>
    <form>
      <div>
        <input type="email" name="email" id="email" placeholder="Email" class="border border-gray-300 rounded-md" required />
      </div>
      <div>
        <input type="password" name="password" id="password" placeholder="Password" class="border border-gray-300 rounded-md" required />
      </div>
      <div>
        <input type="password" name="repeat-password" id="repeat-password" placeholder="Repeat-Password" class="px-3 py-1 mt-2 border border-gray-300 rounded-md" required />
      </div>
      <button type="submit" class="text-white font-bold bg-emerald-600 rounded-md w-fit hover:bg-emerald-700">Sign-up</button>
    </form>
  </div>
</template>

<script lang="ts" setup>
definePageMeta({
  layout: "form",
});
</script>

<style>
button, input {
padding: 4px 12px;
margin-top: 10px;
}
</style>
