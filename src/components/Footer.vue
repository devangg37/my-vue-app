<template>
<footer class="text-center">
  <div class="container pt-2">
    <div class="bg-blue-900 md:px-7 md:py-7 px-2 py-4">
      <form action="">
        <div class="gap-4 flex flex-row justify-around items-center">
          <div class="text-white md:text-3xl hidden md:inline">
            <p class="">
              <strong class="">Sign Up To Get Latest Updates</strong>
            </p>
          </div>

          <div class="flex flex-row">
            <input
              type="text"
              class="
                form-control
                block
                px-3
                py-1.5
                text-base
                font-normal
                text-gray-700
                bg-white bg-clip-padding
                border border-solid border-gray-300
                transition
                ease-in-out
                m-0
                md:h-full h-1/2
                focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none
              "
              id="exampleFormControlInput1"
              placeholder="Email address"/>
            <button type="submit" class="md:h-auto inline-block px-6 py-2 bg-pink-500 text-white font-medium text-xs leading-tight uppercase focus:outline-none focus:ring-0 transition duration-150 ease-in-out">
              Sign Up
            </button>
          </div>
        </div>
      </form>
    </div>
    <div class="grid md:grid-cols-4 md:grid-rows-none auto-rows-auto gap-3 px-5">
      <div class="">
        <h5 class="uppercase font-bold mb-2.5 mt-2.5">RCP PACIFIC</h5>

        <ul class="list-none mb-0 flex flex-col gap-6">
          <li>
            <a class="text-black"><p class="break-words">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.</p></a>
          </li>
          <li>
            <div class="flex gap-7 justify-center">
              <img class ="" src="../assets/fb.jpg" alt="Mountain">
              <img class ="" src="../assets/linkedin.jpg" alt="Mountain">
              <img class ="" src="../assets/twitter.jpg" alt="Mountain">
              <img class ="" src="../assets/youtube.jpg" alt="Mountain">
              <img class ="" src="../assets/Instagram.jpg" alt="Mountain">
            </div>
          </li>
        </ul>
      </div>

      <div class="mb-6">
        <h5 class="uppercase font-bold mb-2.5 mt-2.5">SERVICES</h5>
        <ul class="list-none mb-0">
          <li>
            <a href="#!" class="text-black">Events</a>
          </li>
          <li>
            <a href="#!" class="text-black">Webinars</a>
          </li>
          <li>
            <a href="#!" class="text-black">Blogs</a>
          </li>
          <li>
            <a href="#!" class="text-black">Customer Success</a>
          </li>
          <li>
            <a href="#!" class="text-black">Expert Services</a>
          </li>
          <li>
            <a href="#!" class="text-black">Data Insider</a>
          </li>
          <li>
            <a href="#!" class="text-black">View All Resources</a>
          </li>
        </ul>
      </div>

      <div class="mb-6">
        <h5 class="uppercase font-bold mb-2.5 mt-2.5">RESOURCES</h5>

        <ul class="list-none mb-0">
          <li>
            <a href="#!" class="text-black">Events</a>
          </li>
          <li>
            <a href="#!" class="text-black">Webinars</a>
          </li>
          <li>
            <a href="#!" class="text-black">Blogs</a>
          </li>
          <li>
            <a href="#!" class="text-black">Customer Success</a>
          </li>
          <li>
            <a href="#!" class="text-black">Expert Services</a>
          </li>
          <li>
            <a href="#!" class="text-black">Data Insider</a>
          </li>
          <li>
            <a href="#!" class="text-black">View All Resources</a>
          </li>
        </ul>
      </div>

      <div class="mb-6">
        <h5 class="uppercase font-bold mb-2.5 mt-2.5">COMPANY</h5>

        <ul class="list-none mb-0">
          <li>
            <a href="#!" class="text-black">About Rakuten Fuji</a>
          </li>
          <li>
            <a href="#!" class="text-black">Careers</a>
          </li>
          <li>
            <a href="#!" class="text-black">Leadership</a>
          </li>
        </ul>
      </div>
    </div>
  </div>

  <div class="text-center p-4 bg-slate-600 text-white">
    © Rakuten
  </div>
</footer>
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