<template>
  <nav class="md:px-5 sticky z-40 bg-gray-100 top-0">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
      <div class="relative flex justify-between w-auto static block justify-start">
        <a class="text-xm font-bold leading-relaxed inline-block mr-4">
          <img class="mx-auto scale-75" src="../assets/RCP.jpg" alt="RCP Pacific">
        </a>
      </div>
      <div class="hidden md:flex md:flex-grow"> 
        <ul class="flex flex-row list-none ml-auto items-center">
          <div>
          <li class="nav-item">
            <a class="px-3 text-xm font-bold text-black hover:opacity-75" href="">
              <span class="ml-2">Features</span>
            </a>
          </li>
          </div>
          <div>
          <li class="nav-item">
            <a class="px-3 text-xm font-bold text-black hover:opacity-75" href="">
              <span class="ml-2">About</span>
            </a>
          </li>
          </div>
          <div>
          <li class="nav-item">
            <a class="px-3 text-xm font-bold text-black hover:opacity-75" href="">
                <span class="ml-2">Contact</span>
            </a>
          </li>
          </div>
          <div>
          <li class="nav-item">
            <a class="px-3 text-xm font-bold text-black hover:opacity-75">
              <button class="bg-pink-500 text-white py-2 px-4 rounded-full">
                  Request for DEMO</button>
            </a>
          </li>
          </div>
          <div>
          <li class="nav-item">
            <a class="px-3 text-xm font-bold text-black hover:opacity-75">
              <img class="mx-auto scale-75" src="../assets/icon.jpg" alt="Icon">
            </a>
          </li>
          </div>
        </ul>
      </div>

      <div @click="enableToggle = !enableToggle" class="w-10 mr-2 md:hidden">
        <img src="../assets/toggle.png" class="scale-75"/>
      </div>
      <div v-if="enableToggle" class=" h-[90px] w-screen md:hidden">
        <div class="pl-2 text-center">
            Features
        </div>
        <div class="pl-2 text-center">
            About
        </div>
        <div class=" text-center ">
          <a class="text-xs font-bold text-black hover:opacity-75">
              <button class="bg-pink-500 text-white py-1 px-3 rounded-full">
                  Request for DEMO</button>
          </a>
        </div>
    </div>
    </div>
  </nav>
</template>

<script lang="ts">
export default {
  name: 'Navbar',
  data() {
    return {
      enableToggle: false
    }
  },
  methods: {
  }
}
</script>

<style>
</style>