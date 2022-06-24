<template>
  <div class="w-full flex">
    <Sidebar />
    <div class="w-10/12">
      <header>
        <div class="max-w-screen-xl px-4 py-8 mx-auto sm:py-12 sm:px-6 lg:px-8">
          <div class="sm:justify-between sm:items-center sm:flex">
            <div class="text-center sm:text-left">
              <h1 class="text-2xl font-bold text-red-800 sm:text-3xl">
                Découvert !
              </h1>

              <p class="mt-1.5 text-sm text-gray-500">
                Voici les découverts! 🎉
              </p>
            </div>
          </div>
        </div>
      </header>
      <div class="overflow-hidden overflow-x-auto border border-gray-100 rounded">
  <table class="min-w-full text-sm divide-y divide-gray-200">
    <thead>
      <tr class="bg-gray-50">
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Nom</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Date de naissance</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Découvert</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Plafond</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Agios</th>
      </tr>
    </thead>

    <tbody class="divide-y divide-gray-100">
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">80 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">15/11/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">-28.95 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">600 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">5 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">05/03/1999</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-742.84 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">100 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">80 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">15/11/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">-28.95 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">600 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">5 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">05/03/1999</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-742.84 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">100 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">80 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">15/11/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">-28.95 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">600 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">5 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">05/03/1999</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-742.84 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">100 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">80 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">15/11/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">-28.95 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">600 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">5 €</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">05/03/1999</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">-742.84 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">800 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">100 €</td>
      </tr>

    </tbody>
  </table>
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
