<template>
  <div class="landing-page">
    <section class="landing-hero pt-5">
      <div class="header__bg"></div>
      <div class="container mx-auto relative">
        <Navbar />
        <div class="judl bg-back inline-block items-center pt-10">
          <div class="w-full">
            <h1
              class="text-3xl md:text-4xl pl-32 md:pl-6 text-gray-700 font-semibold mb-4"
            >
              Tempat Bikin Undangan
            </h1>
            <p class="text-gray-700 pl-6 text-xl mb-8">
              Fund the best idea to become <br />
              a real product and be the contributor
            </p>
            <button
              @click="$router.push({ path: '/' })"
              class="block ml-6 bg-orange-button hover:bg-green-button text-white font-semibold px-12 py-3 text-xl rounded-full mb-48"
            >
              Find a Project
            </button>
          </div>
          <div class="w-1/2 flex justify-center">
            <img src="/hero-image@2x.png" alt="crowdfunding project" />
          </div>
        </div>
      </div>
    </section>
    <section class="container mx-auto pt-40">
      <div class="flex justify-between items-center mb-10">
        <div class="w-auto">
          <h2 class="text-3xl text-gray-900 mb-8">
            Only 3 steps to execute <br />
            your bright ideas
          </h2>
        </div>
      </div>
      <div>
        <no-ssr>
          <!-- important to add no-ssr-->

          <carousel :autoplay="true" :margin="10" class="rounded-lg">
            <img
              src="https://placeimg.com/200/200/any?1"
              class="h-56 rounded-lg"
            />

            <img
              src="https://placeimg.com/200/200/any?2"
              class="h-56 rounded-lg"
            />

            <img
              src="https://placeimg.com/200/200/any?3"
              class="h-56 rounded-lg"
            />

            <img
              src="https://placeimg.com/200/200/any?4"
              class="h-56 rounded-lg"
            />
          </carousel>
        </no-ssr>
      </div>
    </section>
    <section class="container mx-auto pt-24"></section>
    <Footer />
  </div>
</template>

<script></script>
