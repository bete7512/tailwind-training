
<template>
  <div class="w-full  h-screen bg-green-800 bg-cover bg-center">
    <div class="flex mx-20 pt-10">
      <div class="flex text-3xl w-1/2 text-white justify-start font-bold font">
        <h1>INSURANCE</h1>
      </div>
      <div class="flex justify-end space-x-6 text-white w-1/2">
        <div class="text-lg">
          <router-link to="">Home</router-link>
        </div>
        <div class="text-lg">
          <router-link to="">Service</router-link>
        </div>
        <div class="text-lg">
          <router-link to="">Insurance Service</router-link>
        </div>
        <div class="text-lg inline-flex bg-amber-400 text-black w-32 h-10 rounded-md">
          <router-link to="" class="inline-flex px-7 py-1">Sign in</router-link>
        </div>
      </div>
    </div>
    <div class="flex mt-20 mx-20">
      <div class="w-1/2">
        <div>
          <div class="text-6xl font-extrabold text-white">
            <h1>Are You Covered? Home, Life, & Auto Insurance.</h1>
          </div>
          <div class="text-white mt-1">Proin eget tortor risus. Praesent sapien massa, convallis a pellentesque nec,
            egestas non nisi. Donec rutrum congue leo eget malesuada. </div>
          <div class="flex mt-8 space-x-2"><button
              class="w-36 h-16 rounded-md bg-amber-400 inline-flex items-center px-4">
              <router-link :to="{ name: 'main' }" class="">GET
                STARTED</router-link>
            </button><button class="w-48 h-16 rounded-md inline-flex items-center px-4"><span class="">WATCH THE
                VIDEO</span></button></div>
          <div class="space-x-4 flex mt-32 ">
            <div class="bg-white rounded-md w-32 h-10"></div>
            <div class="bg-white rounded-md w-32 h-10 "></div>
            <div class="bg-white rounded-md w-32 h-10"></div>
          </div>
        </div>
      </div>
      <div class="flex items-center w-1/2">
        <img
          src="https://img.freepik.com/premium-photo/gorgeous-elegant-sensual-blonde-woman-wearing-fashion-black-dress_149155-246.jpg?size=626&ext=jpg&ga=GA1.2.1143210034.1657986480"
          alt="" class="h-full pr-20 rounded-lg ">
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
</script>
