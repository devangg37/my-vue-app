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
<div class="flex justify-center">
<div id="default-carousel" class="relative h-96 md:w-1/2 pt-10" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="overflow-hidden relative h-80 rounded-lg md:flex md:flex-row md:justify-evenly">
         <!-- Item 1 -->
        <div class="hidden duration-400 ease-linear h-72 flex flex-col items-center md:w-1/2 w-auto shadow-lg" data-carousel-item="active">
            <div class="min-h-[40%]">
                <img src="../assets/img-card-1.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-400 ease-linear h-72 flex flex-col items-center md:w-1/2 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/img-card-2.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-400 ease-linear h-72 flex flex-col items-center md:w-1/2 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/img-card-3.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>

        <div class="hidden duration-200 ease-linear h-72 flex flex-col items-center md:w-1/2 w-auto shadow-lg" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/img-card-3.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly px-5">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="flex absolute bottom-5 left-1/2 z-30 space-x-3 -translate-x-1/2 pt-10">
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="3"></button>
    </div>
    <!-- Slider controls -->
</div>
</div>  
</template> 


<style>
</style>