<template>
  <div class="md:mx-auto max-w-4xl mt-20" >
    <div class="flex flex-wrap justify-center mb-10">
      <div class="md:w-1/3 w-full px-10">
        <h1 class="text-gray-900 text-3xl">About Me</h1>
      </div>
      <div class="md:w-2/3 w-full px-10">
        <p class="text-gray-600 text-xl border-b pb-4">
          Hello! I'm Ruslan, a
          <span class="text-gray-600">software engineer</span>
          based in Germany Munich.
          <br />I enjoy
          <span class="text-gray-600">creating software</span>, whether that be
          <span class="text-gray-600">websites, applications</span>, or even
          <span class="text-gray-600">games</span>. My goal is always to build products that provide
          <span
            class="text-gray-600"
          >responsive and performant</span> experiences.
          <br/>
          Shortly after receiving my
          <span
            class="text-gray-600"
          >master's degree from the Technical University of Munich</span>, I joined the cloud engineering team at Rohde & Schwarz where I worked on their cloud infrastructure for about 2 years. 
          <br/>
          <br/>
          <span>
            <a href="lebenslauf.pdf" class="text-yellow-600 hover:text-yellow-700 " download="LebenslaufRuslan.pdf">
              <button>Download CV here</button>
            </a>
          </span>
        </p>
      </div>
    </div>

    <div class="flex flex-wrap justify-center">
      <div class="md:w-1/3 w-full px-10 mb-5 md:mb-0">
        <h1 class="text-gray-900 text-3xl">My Services</h1>
      </div>
      <div class="md:w-2/3 w-full px-10">
        <div class="border-b pb-4 mt-3 mb-5" v-for="service in services" :key="service.name">
          <a
            class="flex items-center cursor-pointer select-none"
            @click="service.show=!service.show"
          >
            <h1 class="text-gray-900 text-xl">{{service.name}}</h1>
            <img
              src="../assets/arrowDown.svg"
              alt
              class="h-2 ml-3 transition ease-in duration-300"
              :class="{'transform rotate-180': service.show}"
            />
          </a>
          <transition name="slide-fade">
            <p v-if="service.show" class="text-gray-900 my-3 text-xl">{{service.dropDown}}</p>
          </transition>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    callIT() {
      console.log("hallo world");
      this.show = !this.show;
    }
  },
  data() {
    return {
      services: [
        {
          name: "Web development",
          show: false,
          dropDown:
            "JavaScript · VueJs · React ·  NodeJs · Express · Flutter  · Tailwind · Linux · Docker · GIT · Strapi · Python"
        },
        {
          name: "Mobile Application",
          show: false,
          dropDown: "Swift · Flutter"
        },
        {
          name: "Cloud development",
          show: false,
          dropDown:
            "Kubernetes · OpenShift · Linux · Terraform · GO Lang · Kubernetes Operator"
        },
        {
          name: "Game development",
          show: false,
          dropDown: "Unity 3D · C# · Blender"
        },
        {
          name: "UX Design",
          show: false,
          dropDown: "Adobe XD · Sketch"
        }
      ]
    };
  }
};
</script>

<style>



.slide-fade-enter-active {
  transition: all 0.3s ease-out;
}

.slide-fade-leave-active {
  transition: all 0.3s ease-in;
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateY(-20px);
  opacity: 0;
}

.acordionContent {
  transition: all 200ms linear;
}
</style>