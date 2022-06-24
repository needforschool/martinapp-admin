<template>
  <div class="w-full flex">
    <Sidebar />
    <div class="w-10/12">
      <header>
    <div class="max-w-screen-xl px-4 py-8 mx-auto sm:py-12 sm:px-6 lg:px-8">
      <div class="sm:justify-between sm:items-center sm:flex">
        <div class="text-center sm:text-left">
          <h1 class="text-2xl font-bold text-gray-900 sm:text-3xl">
            Bienvenue, Théo!
          </h1>

          <p class="mt-1.5 text-sm text-gray-500">
            Bienvenue sur la plateforme bancaire !🎉
          </p>
        </div>

        <div class="flex flex-col gap-4 mt-4 sm:flex-row sm:mt-0 sm:items-center">
          <nuxt-link to="/">
            <button
              class="inline-flex items-center justify-center px-5 py-3 text-gray-500 transition border border-gray-200 rounded-lg hover:text-gray-700 hover:bg-gray-50 focus:outline-none focus:ring"
              type="button"
            >
              <span class="text-sm font-medium"> Retour sur la page acceuil </span>

              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-4 h-4 ml-1.5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                />
              </svg>
            </button>
          </nuxt-link>
        </div>
      </div>
    </div>
        </header>
        <div class="flex flex-col md:flex-row">
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-4xl font-bold text-indigo-600">12 456 765 €</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Capital Client</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-5xl font-bold text-green-600">785</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Clients</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-5xl font-bold text-red-600">7</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Clients à découvert</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
        </div>
        <div class="flex flex-col md:flex-row">
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-5xl font-bold text-yellow-600">138</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Crédit en cours</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-5xl font-bold text-pink-600">783</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Livret A</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
          <a
      href=""
      class="flex flex-col justify-between p-8 transition-shadow bg-white rounded-sm shadow-xl group hover:shadow-lg w-3/12 m-4"
    >
      <div>
        <h5 class="text-5xl font-bold text-purple-600">4 424 €</h5>
        <div class="pt-2 mt-4 border-t-2 border-indigo-100">
          <p class="text-sm font-medium tracking-widest text-gray-500 uppercase">Argent génére ce mois-ci</p>
        </div>
      </div>

      <div class="inline-flex items-center mt-16 text-indigo-600">
        <p class="text-lg font-medium">En savoir plus</p>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 ml-3 transition-transform transform group-hover:translate-x-3"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </div>
          </a>
        </div>
    </div>
  </div>
</template>

<script>
import Sidebar from '~/components/Sidebar.vue'
export default {
  components: { Sidebar },
  name: "IndexPage",
  // layout: "default",
}
</script>

<style lang="scss">
h1 {
  margin: 0;
}
</style>
