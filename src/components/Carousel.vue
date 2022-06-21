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
<div class="flex flex-col items-center md:py-5 py-2">
        <div class="text-blue-900 text-2xl font-bold md:text-3xl">
            Success Stories
        </div>
        <div class="flex flex-col text-center md:px-10 px-5 text-xs md:text-xl py-3">
            <p class="break-words">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus </p>
        </div>
</div>
<!-- <div class="md:flex md:justify-around"> -->
<div class="relative px-10 h-96 pt-5 w-auto flex flex-col items-center" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="overflow-hidden relative h-80 w-full md:w-1/4 rounded-lg">
         <!-- Item 1 -->
        <div class="duration-900 ease-linear h-80 shadow-lg" data-carousel-item="active block">
            <div class="min-h-[40%]">
                <img src="../assets/walmart.jpg" class="mx-auto" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="duration-900 ease-linear h-80 shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/NASA.jpg" class="mx-auto" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="duration-900 ease-linear h-80 shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/cocacola.jpg" class="mx-auto" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>

        <div class="duration-900 ease-linear h-80 shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/pg.jpg" class="mx-auto" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat .</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="flex justify-center relative space-x-3 pt-5">
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
    </div>
    <!-- Slider controls -->
</div>
<!-- </div>   -->
</template> 


<style>
</style>