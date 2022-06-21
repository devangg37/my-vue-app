<script lang="ts">
export default {
  name: 'Carousel',
  data() {
    return {
    }
  },
  methods: {
  }
}
</script>


<template>
<!-- <div class="md:flex md:justify-around"> -->
<div id="default-carousel" class="h-96 md:pt-10 pt-5 md:w-full w-auto" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="relative h-80 w-full rounded-lg">
         <!-- Item 1 -->
        <div class="duration-900 ease-linear h-72 flex flex-col items-center md:w-1/4 w-auto shadow-lg" data-carousel-item="active">
            <div class="min-h-[40%]">
                <img src="../assets/walmart.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="duration-900 ease-linear h-72 flex flex-col items-center md:w-1/4 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/NASA.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="duration-900 ease-linear h-72 flex flex-col items-center md:w-1/4 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/cocacola.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>

        <div class="duration-900 ease-linear h-72 flex flex-col items-center md:w-1/4 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/pg.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>

        <div class="duration-900 ease-linear h-72 flex flex-col items-center md:w-1/4 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/bmw.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="flex absolute bottom-5 left-1/2 z-30 space-x-3 -translate-x-1/2 md:pt-10">
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button>
    </div>
    <!-- Slider controls -->
</div>
<!-- </div>   -->
</template> 


<style>
</style>