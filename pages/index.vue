<template>
  <div class="h-screen flex flex-col">
    <header>
      <div class="shadow-xl block fixed w-full z-10 bg-white top-0" }>
        <nav>
          <div class="container mx-auto">
            <div class="relative flex items-center justify-between h-16">
              <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
                <a href="/" class="flex-shrink-0 flex items-center font-bold text-2xl">da.nblo.ws</a>
              </div>
            </div>
          </div>
        </nav>
      </div>
    </header>
    <main class="mt-24 container mx-auto flex-1 overflow-y-auto">
      <h1 class="text-6xl font-bold mb-12">Dan Blows</h1>
      <div class="flex">
        <div class="flex-initial">
          <img src="~/assets/images/dan-blows.jpg" />
        </div>
        <p class="text-4xl pl-10 max-w-prose leading-relaxed">
          I'm Dan Blows, a <span class="bg-yellow italic">web developer</span> and <span class="bg-yellow italic">engineering manager</span>
          from the UK. This is my personal website, where you can <a class="underline" href="#">read my CV</a>, <a
          class="underline" href="#">see examples of my work</a>, or <a class="underline" href="#">get in touch</a>.
        </p>
      </div>
    </main>
    <footer class='w-full text-center border-t border-grey p-4 bg-black text-white' }>
      Dan Blows &copy;
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
