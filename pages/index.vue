<template>
  <div>
    <div class="px-4 py-3 text-white bg-indigo-700">
      <p class="text-sm font-medium text-center">
        Découvrez notre nouvelle application bancaire !

        <nuxt-link class="underline" to="about">
          En savoir plus &rarr;
        </nuxt-link>
      </p>
    </div>
    <section class="relative bg-white">
      <img
        class="absolute inset-0 object-[75%] sm:object-[25%] object-cover w-full h-full opacity-25 sm:opacity-100"
        src="https://images.unsplash.com/photo-1609429019995-8c40f49535a5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1169&q=80"
        alt="Couple on a bed with a dog"
      />

      <div
        class="hidden sm:block sm:inset-0 sm:absolute sm:bg-gradient-to-r sm:from-white sm:to-transparent"
      ></div>

      <div
        class="relative max-w-screen-xl px-4 py-32 mx-auto lg:h-screen lg:items-center lg:flex"
      >
        <div class="max-w-xl text-center sm:text-left">
          <h1 class="text-3xl font-extrabold sm:text-5xl">
            Gerez vos clients
            <strong class="font-extrabold text-indigo-700 sm:block">
              COMME EN 2050
            </strong>
          </h1>

          <p class="max-w-lg mt-4 sm:leading-relaxed sm:text-xl">
            Bienvenue sur la MACRON'APP, l'application préféré des
            <span class="line-through">voleurs</span> banquiers.
          </p>

          <div class="flex flex-wrap gap-4 mt-8 text-center">
            <nuxt-link
              class="block w-full px-12 py-3 text-sm font-medium text-white rounded shadow bg-indigo-600 sm:w-auto active:bg-indigo-500 hover:bg-indigo-700 focus:outline-none focus:ring"
              to="login"
            >
              Se connecter
            </nuxt-link>

            <nuxt-link
              class="block w-full px-12 py-3 text-sm font-medium bg-white rounded shadow text-indigo-600 sm:w-auto hover:text-indigo-700 active:text-indigo-500 focus:outline-none focus:ring"
              to="about"
            >
              En savoir plus
            </nuxt-link>
          </div>
        </div>
      </div>
    </section>
    <div>
      <div class="flex flex-wrap overflow-hidden">
        <div class="w-1/3 overflow-hidden md:w-full lg:w-1/3">
          <!-- Column Content -->
          <a
            href=""
            class="relative block p-8 pb-24 border-t-4 border-indigo-600 rounded-sm shadow-xl m-3 my-10"
          >
            <h5 class="text-4xl font-bold">+37</h5>
            <p class="mt-4 text-lg font-medium text-gray-500">
              Gerez plus de 37 clients en simultanés grace à notre nouveau
              dashboard !
            </p>

            <span class="absolute bottom-8 right-8">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-10 h-10 text-indigo-600"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M13 10V3L4 14h7v7l9-11h-7z"
                />
              </svg>
            </span>
          </a>
        </div>

        <div class="w-1/3 overflow-hidden md:w-full lg:w-1/3">
          <!-- Column Content -->
          <a
            href=""
            class="relative block p-8 pb-24 border-t-4 border-indigo-600 rounded-sm shadow-xl m-3 my-10"
          >
            <h5 class="text-4xl font-bold">-10s</h5>
            <p class="mt-4 text-lg font-medium text-gray-500">
              une connexion et un chargement toujours plus rapide grace au
              technologie utilisé
            </p>

            <span class="absolute bottom-8 right-8">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-10 h-10 text-indigo-600"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M13 10V3L4 14h7v7l9-11h-7z"
                />
              </svg>
            </span>
          </a>
        </div>

        <div class="w-1/3 overflow-hidden md:w-full lg:w-1/3">
          <!-- Column Content -->
          <a
            href=""
            class="relative block p-8 pb-24 border-t-4 border-indigo-600 rounded-sm shadow-xl m-3 my-10"
          >
            <h5 class="text-4xl font-bold">100€</h5>
            <p class="mt-4 text-lg font-medium text-gray-500">
              Gagnez de l'argent facilement tout les jours en vous connectant 💰
            </p>

            <span class="absolute bottom-8 right-8">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-10 h-10 text-indigo-600"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M13 10V3L4 14h7v7l9-11h-7z"
                />
              </svg>
            </span>
          </a>
        </div>
      </div>
    </div>
    <div>
      <section class="text-white bg-indigo-600">
        <div class="max-w-screen-xl px-4 py-16 mx-auto sm:px-6 lg:px-8">
          <div class="max-w-xl">
            <h2 class="text-4xl font-bold sm:text-6xl">
              Une année incroyable !
            </h2>

            <p class="mt-4 sm:text-xl">
              L'année 2021 s'est terminée d'une façon incroyable pour tout
              l'équipe de la MACRON'APP ! La société a été introduite en bourse
              en Suisse, en Andorre et au Luxembourg.
            </p>
          </div>

          <ul class="grid grid-cols-1 gap-8 mt-8 sm:grid-cols-2 lg:grid-cols-3">
            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">42</p>
              <p class="mt-1 text-xl font-medium">Banques en France</p>
            </li>

            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">+190K€</p>
              <p class="mt-1 text-xl font-medium">Argent volé</p>
            </li>

            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">20+</p>
              <p class="mt-1 text-xl font-medium">Rolex</p>
            </li>

            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">+83</p>
              <p class="mt-1 text-xl font-medium">Recrutements par an</p>
            </li>

            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">1</p>
              <p class="mt-1 text-xl font-medium">Enquetes judiciaires</p>
            </li>

            <li class="p-8 shadow-xl rounded-xl">
              <p class="text-3xl font-extrabold">6</p>
              <p class="mt-1 text-xl font-medium">Tentative de fraudes</p>
            </li>
          </ul>
        </div>
      </section>
    </div>
    <div>
      <section>
        <div class="max-w-screen-xl px-4 py-16 mx-auto sm:px-6 lg:px-8">
          <div class="grid grid-cols-1 gap-8 lg:gap-16 lg:grid-cols-2">
            <div
              class="relative h-64 overflow-hidden rounded-lg sm:h-80 lg:h-full lg:order-last"
            >
              <img
                class="absolute inset-0 object-cover w-full h-full"
                src="https://www.hyperui.dev/photos/man-1.jpeg"
                alt="Man using a computer"
              />
            </div>

            <div class="lg:py-24">
              <h2 class="text-3xl font-bold sm:text-4xl">
                Augmentation de votre capital
              </h2>

              <p class="mt-4 text-gray-600">
                Grace à notre application, nos placements, et votre confiance,
                nous pouvons vous prommettre une augmentation de 69% avec un
                taux d'interêt de 17 ! (record en France)
              </p>

              <nuxt-link
                class="inline-flex items-center px-8 py-3 mt-8 text-white bg-indigo-600 border border-indigo-600 rounded hover:bg-transparent hover:text-indigo-600 active:text-indigo-500 focus:outline-none focus:ring"
                to="login"
              >
                <span class="text-sm font-medium"> Commencer ! </span>

                <svg
                  class="w-5 h-5 ml-3"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M17 8l4 4m0 0l-4 4m4-4H3"
                  />
                </svg>
              </nuxt-link>
            </div>
          </div>
        </div>
      </section>
    </div>
    <div class="max-w-5xl px-4 py-8 mx-auto">
      <section class="p-8 bg-gray-100 rounded-lg">
        <div class="grid grid-cols-1 gap-12 sm:grid-cols-3 sm:items-center">
          <div class="relative">
            <div class="aspect-w-1 aspect-h-1">
              <img
                src="https://www.hyperui.dev/photos/man-5.jpeg"
                alt=""
                class="object-cover rounded-lg"
              />
            </div>

            <div
              class="absolute inline-flex px-4 py-2 bg-white rounded-lg shadow-xl -bottom-4 -right-4"
            >
              <span
                class="inline-block w-12 h-10 bg-gray-100 rounded-lg"
              ></span>
            </div>
          </div>

          <blockquote class="sm:col-span-2">
            <p class="text-xl font-medium sm:text-2xl">
              "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt
              perspiciatis cumque neque ut nobis excepturi, quasi iure quisquam
              autem alias."
            </p>

            <cite class="inline-flex items-center mt-8 not-italic">
              <span class="hidden w-6 h-px bg-gray-400 sm:inline-block"></span>
              <p class="text-sm text-gray-500 uppercase sm:ml-3">
                <strong>Titi</strong>, CEO MACRON APP.
              </p>
            </cite>
          </blockquote>
        </div>
      </section>
    </div>
    <div class="space-y-4 m-10"></div>
    <div>
      <footer class="bg-gray-50">
        <div class="max-w-screen-xl px-4 py-16 mx-auto sm:px-6 lg:px-8">
          <div class="grid grid-cols-1 gap-8 lg:grid-cols-3">
            <div>
              <span class="block w-32 h-10 bg-gray-200 rounded-lg"></span>

              <p class="max-w-xs mt-4 text-sm text-gray-500">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Voluptas, accusantium.
              </p>

              <div class="flex mt-8 space-x-6 text-gray-500">
                <a
                  class="hover:opacity-75"
                  href=""
                  target="_blank"
                  rel="noreferrer"
                >
                  <span class="sr-only"> Facebook </span>

                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </a>

                <a
                  class="hover:opacity-75"
                  href=""
                  target="_blank"
                  rel="noreferrer"
                >
                  <span class="sr-only"> Instagram </span>

                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </a>

                <a
                  class="hover:opacity-75"
                  href=""
                  target="_blank"
                  rel="noreferrer"
                >
                  <span class="sr-only"> Twitter </span>

                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
                    />
                  </svg>
                </a>

                <a
                  class="hover:opacity-75"
                  href=""
                  target="_blank"
                  rel="noreferrer"
                >
                  <span class="sr-only"> GitHub </span>

                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </a>

                <a
                  class="hover:opacity-75"
                  href=""
                  target="_blank"
                  rel="noreferrer"
                >
                  <span class="sr-only"> Dribbble </span>

                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </a>
              </div>
            </div>

            <div
              class="grid grid-cols-1 gap-8 lg:col-span-2 sm:grid-cols-2 lg:grid-cols-4"
            >
              <div>
                <p class="font-medium">Company</p>

                <nav class="flex flex-col mt-4 space-y-2 text-sm text-gray-500">
                  <a class="hover:opacity-75" href=""> About </a>
                  <a class="hover:opacity-75" href=""> Meet the Team </a>
                  <a class="hover:opacity-75" href=""> History </a>
                  <a class="hover:opacity-75" href=""> Careers </a>
                </nav>
              </div>

              <div>
                <p class="font-medium">Services</p>

                <nav class="flex flex-col mt-4 space-y-2 text-sm text-gray-500">
                  <a class="hover:opacity-75" href=""> 1on1 Coaching </a>
                  <a class="hover:opacity-75" href=""> Company Review </a>
                  <a class="hover:opacity-75" href=""> Accounts Review </a>
                  <a class="hover:opacity-75" href=""> HR Consulting </a>
                  <a class="hover:opacity-75" href=""> SEO Optimisation </a>
                </nav>
              </div>

              <div>
                <p class="font-medium">Helpful Links</p>

                <nav class="flex flex-col mt-4 space-y-2 text-sm text-gray-500">
                  <a class="hover:opacity-75" href=""> Contact </a>
                  <a class="hover:opacity-75" href=""> FAQs </a>
                  <a class="hover:opacity-75" href=""> Live Chat </a>
                </nav>
              </div>

              <div>
                <p class="font-medium">Legal</p>

                <nav class="flex flex-col mt-4 space-y-2 text-sm text-gray-500">
                  <a class="hover:opacity-75" href=""> Privacy Policy </a>
                  <a class="hover:opacity-75" href=""> Terms & Conditions </a>
                  <a class="hover:opacity-75" href=""> Returns Policy </a>
                  <a class="hover:opacity-75" href=""> Accessibility </a>
                </nav>
              </div>
            </div>
          </div>

          <p class="mt-8 text-xs text-gray-500">&copy; 2022 Company Name</p>
        </div>
      </footer>
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
