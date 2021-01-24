<template>
  <header class="flex items-center">
    <div style="height: 54px" class="pl-3 md:pr-10">
      <img src="/logo.svg" alt="logo" class="h-full" />
    </div>
    <ul class="hidden md:flex md:items-center">
      <li>
        <Nuxt-Link
          class="text-gray-800 hover:text-teal-500 hover:underline text-lg px-4 py-3"
          to="/"
          >Home</Nuxt-Link
        >
      </li>
      <li>
        <Nuxt-Link
          class="text-gray-800 hover:text-teal-500 hover:underline text-lg px-4 py-3"
          to="/projects"
          >Project</Nuxt-Link
        >
      </li>
      <li>
        <Nuxt-Link
          class="text-gray-800 hover:text-teal-500 hover:underline text-lg px-4 py-3"
          to="/features"
          >Features</Nuxt-Link
        >
      </li>
      <li>
        <Nuxt-Link
          class="text-gray-800 hover:text-teal-500 hover:underline text-lg px-4 py-3"
          to="/story"
          >Success Stories</Nuxt-Link
        >
      </li>
    </ul>
    <ul class="flex md:flex ml-16 md:ml-auto md:items-center md:mt-2">
      <li>
        <Nuxt-Link
          to="/register"
          class="inline-block bg-transparent border-gray-500 border hover:bg-green-button hover:bg-opacity-25 text-gray-800 font-light w-11/12 md:w-40 text-center px-3 py-1 text-lg rounded-full mr-4"
        >
          Sign Up
        </Nuxt-Link>
      </li>
      <li>
        <Nuxt-Link
          to="/login"
          class="inline-block bg-transparent border bg-green-button hover:bg-orange-button text-gray-200 font-normal w-24 md:w-40 text-center px-6 py-1 text-lg rounded-full"
        >
          Login
        </Nuxt-Link>
      </li>
    </ul>
  </header>
</template>
