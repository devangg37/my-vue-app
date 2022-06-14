<template>
  <div class="relative grid auto-rows-auto">
    <div class="relative md:grid md:grid-cols-2 md:gap-4 md:py-2 items-center">
      <div class="space-y-5">
        <div class="flex flex-col md:space-y-5 space-y-3">
          <div class="text-xl md:text-6xl space-y-1.5">
              <span class = "text-pink-500">Pacific</span>
              <span class = "text-blue-900"> Centralized Data Storage in RAW</span>
          </div>
          <div class=" text-xs md:text-xl">
            Store Data in RAW and unstructured data then select and organize the data when needed from the centralized DataLake.
          </div>
          <div class="text-xs md:text-xl">
            Our AI Engine will help you visuialize the data in real-time when you make a search query.
          </div>
        </div>
        <div class = "flex flex-row md:space-x-7 space-x-8 md:justify-start">
            <div>
              <button class="md:px-3 px-2 md:py-2 py-2 rounded-full text-white bg-pink-500 md:py-2 py-2 md:px-10 px-5 md:text-xl text-xs">WHY PACIFIC</button>
            </div>
            <div>
              <button class="md:px-3 px-2 md:py-2 py-2 rounded-full text-blue-900 border border-blue-900 md:py-2 py-2 md:px-10 px-5 hover:text-pink-500 hover:border-pink-500 md:text-xl text-xs">Learn More</button>
            </div> 
        </div>
      </div>
      <div>
        <img class="mx-auto scale-75 md:scale-100" src="../assets/Video.jpg" alt="Mountain">
      </div>
    </div>
    <div>
      <div class="flex flex-col items-center md:space-y-2 space-y-2">
        <div class="md:text-5xl text-blue-900 font-bold">
          DataLake Features
        </div>
        <div class="md:text-xl text-xs">
          We provide complete or ala-carte engineering solutions to your data needs.
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Pacific-Info',
  data() {
    return {
    }
  },
  methods: {
  }
}
</script>

<style>
</style>