<template>
  <div class="py-12 mt-10">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <!-- <p
          class="text-base leading-6 text-indigo-600 font-semibold tracking-wide uppercase"
        >Services</p>-->
        <h1
          class="text-2xl tracking-tight leading-10 font-hairline hairline text-gray-900 sm:text-2xl sm:leading-none md:text-4xl"
        >Currently working on</h1>
        <!-- <p
          class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto"
        >Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>-->
      </div>

      <div class="mt-20 flex flex-wrap-reverse justify-center">
        <div class="md:w-1/2 mt-10 md:mt-0 w-full">
          <a href="https://www.safeat.de" target="_blank">
            <img
              alt="safeat.de"
              src="../assets/Safeat.png"
              class="mx-auto border shadow-sm transform hover:scale-105 transition ease-in duration-200"
            />
          </a>
        </div>
        <div class="md:w-1/2 w-full md:px-10 flex flex-col justify-between text-left mt-4 md:mt-0">
          <div>
            <h4 class="text-2xl leading-6 font-medium text-gray-900">Saf'Eat Progressive Web App</h4>
            <div class>
              <p class="mt-5 text-xl text-gray-600">
                I'm the CEO of SafEat UG. Safeat is a progressive web app that digitizes the traditional ordering and payment process in restaurants.
                <br />In this project I am responsible for the Front end and Back end programming.
                The project is realized as a progressive web app in Vue Js.
              </p>

              <br />
              <p class="mt-5 text-xl text-gray-600">Created: 20.07.2020</p>
              <br />
              <a
                href="https://www.safeat.de"
                class="hover:text-yellow-700 text-xl"
                target="_blank"
              >www.safeat.de</a>

              <div class="mt-10">
                <h1>
                  Frontend:
                  <span class="text-gray-700">Vue Js · Tailwind CSS</span>
                </h1>
                <h1>
                  Backend:
                  <span class="text-gray-700">Node Js · Strapi · Mongo DB · Socket IO</span>
                </h1>
                <h1>
                  Payment:
                  <span class="text-gray-700">Stripe · PayPal Api</span>
                </h1>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="flex border-b my-10 w-full"></div>
      <!-- Paarfit -->
      <div class="mt-20 flex flex-wrap justify-center">
        <div class="md:w-1/2 w-full md:px-10 flex flex-col justify-between text-left mt-4 md:mt-0">
          <div>
            <h4
              class="text-2xl leading-6 font-medium text-gray-900"
            >Paarfit Progressive Web App & IOS App</h4>
            <div class>
              <p class="mt-5 text-xl text-gray-600">
                Paarfit finally brings fitness for couples into the living room.
                <br />
                <br />In this project I am responsible for the Front end and Back end programming.
                <br>
                
              </p>

              <br />
              <div class="px-1 py-1 rounded-full bg-orange-500 text-white text-center shadow"> In closed beta</div>

              <br />
              <p class="mt-5 text-xl text-gray-600">Created: 10.03.2020</p>
              <br />
              <!-- <a
                href="https://www.safeat.de"
                class="hover:text-yellow-700 text-xl"
                target="_blank"
              >www.safeat.de</a>-->

              <div class="mt-10">
                <h1>
                  Frontend:
                  <span class="text-gray-700">Vue Js · Tailwind CSS</span>
                </h1>
                <h1>
                  App:
                  <span class="text-gray-700">Flutter</span>
                </h1>
                <h1>
                  Backend:
                  <span class="text-gray-700">Node Js · Express · Mongo DB · Docker</span>
                </h1>
                <h1>
                  Payment:
                  <span class="text-gray-700">Stripe</span>
                </h1>
              </div>
            </div>
          </div>
        </div>
        <div class="md:w-1/2 md:mt-0 mt-10 w-full">
          <a>
            <img
              alt="paarfit.de"
              src="../assets/PaarfitMockup.png"
              class="mx-auto transform hover:scale-105 transition ease-in duration-200"
            />
          </a>
        </div>
      </div>

      <!-- <div class="flex items-center mt-5 md:mt-0 justify-center">
        <span class="bg-orange-500 border border-gray-200 w-4 h-4 rounded-full mx-2"></span>
        <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
        <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
      </div>-->
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>