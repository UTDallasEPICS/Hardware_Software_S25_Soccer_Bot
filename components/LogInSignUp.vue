<!--overlay for the login button on the top right side of the navigation bar-->
<template>
  <div class="flex md:flex md:flex-grow flex-row-reverse space-x-3 mt-5 mr-4 mb-2">
    <div class="">
      <!--Here, call funciton login on button click-->
      <button
          class="hover:text-gray-300 transition font-semibold duration-400 text-white font-bold py-2 px-5 rounded-lg"
          style="background-color:#154734" @click="login">Log In</button>
    </div>
  </div>
</template>

<script setup lang="ts">
//Just switches the page to the login page.
const login = async () => { window.location.href = 'api/login' }
</script>

<style></style>