<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
    <p class="text-3xl text-gray-700 font-bold mb-5">
      Welcome!
    </p>
    <p class="text-gray-500 text-lg">
      Vue and Tailwind CSS in action
    </p>
 </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
