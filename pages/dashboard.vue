<template>
  <div class="w-full flex">
    <div class="flex flex-col justify-between h-screen bg-white border-r w-2/12">
    <div class="px-4 py-6">
    <span class="block w-32 h-10 bg-gray-200 rounded-lg"></span>

    <nav class="flex flex-col mt-6 space-y-1">
      <a
        href=""
        class="flex items-center px-4 py-2 text-gray-700 bg-gray-100 rounded-lg"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-5 h-5 opacity-75"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
          />
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
          />
        </svg>

        <span class="ml-3 text-sm font-medium"> Dashboard </span>
      </a>

      <details class="group">
        <summary
          class="flex items-center px-4 py-2 text-gray-500 rounded-lg cursor-pointer hover:bg-gray-100 hover:text-gray-700"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5 h-5 opacity-75"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
            />
          </svg>

          <span class="ml-3 text-sm font-medium"> Clients</span>

          <span
            class="ml-auto transition duration-300 shrink-0 group-open:-rotate-180"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                clip-rule="evenodd"
              />
            </svg>
          </span>
        </summary>

        <nav class="mt-1.5 ml-8 flex flex-col">
          <a
            href=""
            class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5 opacity-75"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M18.364 18.364A9 9 0 005.636 5.636m12.728 12.728A9 9 0 015.636 5.636m12.728 12.728L5.636 5.636"
              />
            </svg>

            <span class="ml-3 text-sm font-medium"> Découvert </span>
          </a>

          <a
            href=""
            class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5 opacity-75"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
              />
            </svg>

            <span class="ml-3 text-sm font-medium"> List</span>
          </a>
        </nav>
      </details>

      <a
        href=""
        class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-5 h-5 opacity-75"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z"
          />
        </svg>

        <span class="ml-3 text-sm font-medium"> Crédit </span>
      </a>

      <a
        href=""
        class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-5 h-5 opacity-75"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"
          />
        </svg>

        <span class="ml-3 text-sm font-medium"> Gestion clients</span>
      </a>

      <details class="group">
        <summary
          class="flex items-center px-4 py-2 text-gray-500 rounded-lg cursor-pointer hover:bg-gray-100 hover:text-gray-700"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5 h-5 opacity-75"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
            />
          </svg>

          <span class="ml-3 text-sm font-medium"> Profil </span>

          <span
            class="ml-auto transition duration-300 shrink-0 group-open:-rotate-180"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                clip-rule="evenodd"
              />
            </svg>
          </span>
        </summary>

        <nav class="mt-1.5 ml-8 flex flex-col">
          <a
            href=""
            class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5 opacity-75"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M10 6H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V8a2 2 0 00-2-2h-5m-4 0V5a2 2 0 114 0v1m-4 0a2 2 0 104 0m-5 8a2 2 0 100-4 2 2 0 000 4zm0 0c1.306 0 2.417.835 2.83 2M9 14a3.001 3.001 0 00-2.83 2M15 11h3m-3 4h2"
              />
            </svg>

            <span class="ml-3 text-sm font-medium"> Informations</span>
          </a>

          <a
            href=""
            class="flex items-center px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-5 h-5 opacity-75"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"
              />
            </svg>

            <span class="ml-3 text-sm font-medium"> Sécurité </span>
          </a>

          <form action="/logout">
            <button
              type="submit"
              class="flex items-center w-full px-4 py-2 text-gray-500 rounded-lg hover:bg-gray-100 hover:text-gray-700"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5 opacity-75"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1"
                />
              </svg>

              <span class="ml-3 text-sm font-medium"> Déconnexion</span>
            </button>
          </form>
        </nav>
      </details>
    </nav>
    </div>

    <div class="sticky inset-x-0 bottom-0 border-t border-gray-100">
      <a href="" class="flex items-center p-4 bg-white hover:bg-gray-50 shrink-0">
        <img
          class="object-cover w-10 h-10 rounded-full"
          src="https://www.hyperui.dev/photos/man-4.jpeg"
          alt="Simon Lewis"
        />

        <div class="ml-1.5">
          <p class="text-xs">
            <strong class="block font-medium">Théo Maudet</strong>

            <span> theo.maudet@icloud.com </span>
          </p>
        </div>
      </a>
    </div>
    </div>
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
export default {
  name: "IndexPage",
  // layout: "default",
}
</script>

<style lang="scss">
h1 {
  margin: 0;
}
</style>
