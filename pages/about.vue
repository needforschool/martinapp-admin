<template>
  <div>
    <header class="bg-gray-50">
      <div class="max-w-screen-xl px-4 py-8 mx-auto sm:py-12 sm:px-6 lg:px-8">
        <div class="sm:justify-between sm:items-center sm:flex">
          <div class="text-center sm:text-left">
            <h1 class="text-2xl font-bold text-gray-900 sm:text-3xl">
              A propos de la MACRON'APP
            </h1>

            <p class="mt-1.5 text-sm text-gray-500">
              Quelque questions / réponses
            </p>
          </div>

          <div
            class="flex flex-col gap-4 mt-4 sm:flex-row sm:mt-0 sm:items-center"
          >
            <nuxt-link
              class="block w-full px-12 py-3 text-sm font-medium bg-white rounded shadow text-indigo-600 sm:w-auto hover:text-indigo-700 active:text-indigo-500 focus:outline-none focus:ring"
              to="/"
            >
              Retour
            </nuxt-link>
          </div>
        </div>
      </div>
    </header>
    <div class="space-y-4 m-10">
      <details class="group">
        <summary
          class="flex items-center justify-between p-4 rounded-lg cursor-pointer bg-gray-50"
        >
          <h5 class="font-medium text-gray-900">Comment avoir confiance ?</h5>

          <svg
            class="flex-shrink-0 ml-1.5 w-5 h-5 transition duration-300 group-open:-rotate-180"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </summary>

        <p class="px-4 mt-4 leading-relaxed text-gray-700">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab hic
          veritatis molestias culpa in, recusandae laboriosam neque aliquid
          libero nesciunt voluptate dicta quo officiis explicabo consequuntur
          distinctio corporis earum similique!
        </p>
      </details>

      <details class="group">
        <summary
          class="flex items-center justify-between p-4 rounded-lg cursor-pointer bg-gray-50"
        >
          <h5 class="font-medium text-gray-900">
            Quel sont les conditions générales d'utilisations ?
          </h5>

          <svg
            class="flex-shrink-0 ml-1.5 w-5 h-5 transition duration-300 group-open:-rotate-180"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </summary>

        <p class="px-4 mt-4 leading-relaxed text-gray-700">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab hic
          veritatis molestias culpa in, recusandae laboriosam neque aliquid
          libero nesciunt voluptate dicta quo officiis explicabo consequuntur
          distinctio corporis earum similique!
        </p>
      </details>

      <details class="group">
        <summary
          class="flex items-center justify-between p-4 rounded-lg cursor-pointer bg-gray-50"
        >
          <h5 class="font-medium text-gray-900">Qui est Macron ?</h5>

          <svg
            class="flex-shrink-0 ml-1.5 w-5 h-5 transition duration-300 group-open:-rotate-180"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </summary>

        <p class="px-4 mt-4 leading-relaxed text-gray-700">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab hic
          veritatis molestias culpa in, recusandae laboriosam neque aliquid
          libero nesciunt voluptate dicta quo officiis explicabo consequuntur
          distinctio corporis earum similique!
        </p>
      </details>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
