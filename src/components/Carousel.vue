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
<div id="default-carousel" class="relative h-80 w -1/2 md:h-80 md:w-1/2" data-carousel="static">
    <!-- Carousel wrapper -->
    <div class="overflow-hidden relative h-72 md:h-72 rounded-lg flex justify-center ">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out h-72 flex flex-col items-center md:w-72" data-carousel-item="active">
            <div class="min-h-[40%]">
                <img src="../assets/img-card-1.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly pt-3">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out h-72 flex flex-col items-center w-72" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/img-card-2.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out h-72 flex flex-col items-center w-72" data-carousel-item>
            <div class="min-h-[40%]">
                <img src="../assets/img-card-3.jpg" class="w- h-full object-contain" />
            </div>
        <!-- Text container-->
            <div class="min-h-[60%] flex flex-col justify-evenly">
                <p class="break-words">Lorem ipsum dolor sit amet praesentium voluptatibus, harum sed in repellendus dicta sequi soluta atque deserunt cupiditate dolores ad recusandae laboriosam suscipit?</p>
                <p class="text-pink-900">Read more</p>
            </div>
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="flex absolute bottom-5 left-1/2 z-30 space-x-3 -translate-x-1/2">
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-blue-500 hover:bg-pink-900" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
    </div>
    <!-- Slider controls -->
</div>
</div>  
</template> 


<style>
</style>