<template>
  <div>
    <div
      class="relative mx-auto max-w-screen-xl px-4 sm:px-6 lg:px-8 flex flex-wrap-reverse justify-center items-center screen border-b"
    >
      <div class="text-center md:text-right md:w-1/2">
        <h2
          class="text-4xl tracking-tight leading-10 font-hairline hairline text-gray-900 sm:text-5xl sm:leading-none md:text-6xl"
        >Ruslan Noschajew</h2>

        <span class="text-gray-600 font-hairline text-2xl typing-demo">Software Developer</span>

        <p class="text-xl text-gray-600 mt-10">
          I'm a
          <span class="text-gray-600">software engineer</span> based in Germany Munich, specialised in building and
          <span
            class="text-gray-600"
          >designing websites, applications</span>, and everything in between.
          <a
            class="hover:text-yellow-800 text-yellow-700"
            href="#leistungen"
          >read more</a>
        </p>
        <div class="mt-5 sm:mt-8 sm:flex justify-center md:justify-end">
          <div class="rounded-md">
            <a
              href="mailto:noschajew.ruslan@gmail.com"
              class="w-full flex items-center justify-center px-3 py-3 border text-base leading-6 font-medium rounded-md text-white bg-gray-900 border-white hover:bg-gray-800 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out md:py-4 lg:text-lg lg:px-10"
            >Contact Me</a>
          </div>
          <div class="mt-3 sm:mt-0 sm:ml-3">
            <a
              href="lebenslauf.pdf"
              class="hover:bg-yellow-600 hover:text-white focus:outline-none w-full flex items-center justify-center px-8 py-3 border border-yellow-600 text-base leading-6 font-medium rounded-md text-gray-600 hover:border-yellow-600 focus:shadow-outline focus:border-indigo-300 transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10"
              download="CVRuslanNoschajew.pdf"
            >Download Resume</a>
          </div>
        </div>
      </div>

      <div class="md:w-1/2 mt-10 flex justify-center items-center">
        <img
          class="object-cover rounded-full profileImageSize border border-yellow-700 p-3 transform transition hover:scale-125 duration-200 ease-in"
          src="../assets/Profiledrawn2.jpeg"
          alt="https://images.unsplash.com/photo-1543610892-0b1f7e6d8ac1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80"
        />
        <!-- https://images.unsplash.com/photo-1534188753412-3e26d0d618d6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2734&q=80 -->
        <!-- https://images.unsplash.com/photo-1543610892-0b1f7e6d8ac1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80 -->
      </div>

      <!-- <SpeechBuble/> -->
      <div class="absolute bottom-0 centerMouse hidden md:block">
        <MouseScrollAnim />
      </div>
    </div>
  </div>
</template>

<script>
// import SocialMediaButtons from './SocialMediaButtons.vue'
import MouseScrollAnim from "./MouseScrollAnimation.vue";
export default {
  components: { MouseScrollAnim }
};
</script>

<style scoped>
.centerMouse {
  right: 50%;
}
.screen {
  height: 50rem;
}
.profileImageSize {
  height: 18rem;
  width: 18rem;
}
</style>