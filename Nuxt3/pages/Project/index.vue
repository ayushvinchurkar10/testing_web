<template>
  <div>
    <h1>Project</h1>
    <br />
    <label for="start">Date: </label>
    <input
      type="date"
      id="start"
      name="trip-start"
      :value="today"
      :min="minDate"
      :max="maxDate"
    />
    <br>
    <ProjectCard />
  </div>
</template>

<script lang="ts" setup>
import { ref } from "vue";


// Get today's date
const today = ref(new Date().toISOString().split("T")[0]);

// Set the minimum and maximum dates if needed
const minDate = ref("2018-01-01");
const maxDate = today;


</script>

<style></style>
