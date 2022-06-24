<template>
  <div class="w-full flex">
    <Sidebar />
    <div class="w-10/12">
      <header>
        <div class="max-w-screen-xl px-4 py-8 mx-auto sm:py-12 sm:px-6 lg:px-8">
          <div class="sm:justify-between sm:items-center sm:flex">
            <div class="text-center sm:text-left">
              <h1 class="text-2xl font-bold text-indigo-800 sm:text-3xl">
                Liste des clients !
              </h1>

              <p class="mt-1.5 text-sm text-gray-500">
                Découvrez les clients ! 🎉
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
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Capital</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Assurances</th>
        <th class="px-4 py-2 font-medium text-left text-gray-900 whitespace-nowrap">Offre</th>
      </tr>
    </thead>

    <tbody class="divide-y divide-gray-100">
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1986</td>
        <td class="px-4 py-2 text-green-700 whitespace-nowrap">12 684.98 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Non</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Classique</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">08/03/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">285.23 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1986</td>
        <td class="px-4 py-2 text-green-700 whitespace-nowrap">12 684.98 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Non</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Classique</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">08/03/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">285.23 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">- 654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1986</td>
        <td class="px-4 py-2 text-green-700 whitespace-nowrap">12 684.98 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Non</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Classique</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">08/03/2001</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">285.23 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1995</td>
        <td class="px-4 py-2 text-yellow-700 whitespace-nowrap">654.45 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">24/05/1986</td>
        <td class="px-4 py-2 text-green-700 whitespace-nowrap">22 684.98 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Non</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Classique</td>
      </tr>
      <tr>
        <td class="px-4 py-2 font-medium text-gray-900 whitespace-nowrap">John Doe</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">08/03/2001</td>
        <td class="px-4 py-2 text-red-700 whitespace-nowrap">- 485.23 €</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Oui</td>
        <td class="px-4 py-2 text-gray-700 whitespace-nowrap">Jeune</td>
      </tr>
      
      

    </tbody>
  </table>
</div>
<ol class="flex justify-center space-x-1 text-xs font-medium m-3">
  <li>
    <a href="/?page=1" class="inline-flex items-center justify-center w-8 h-8 border border-gray-100 rounded">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-3 h-3" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd" />
      </svg>
    </a>
  </li>

  <li>
    <a href="/?page=1" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 1 </a>
  </li>

  <li class="block w-8 h-8 leading-8 text-center text-white bg-blue-600 border-blue-600 rounded">2</li>

  <li>
    <a href="/?page=3" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 3 </a>
  </li>

  <li>
    <a href="/?page=4" class="block w-8 h-8 leading-8 text-center border border-gray-100 rounded"> 4 </a>
  </li>

  <li>
    <a href="/?page=3" class="inline-flex items-center justify-center w-8 h-8 border border-gray-100 rounded">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-3 h-3" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" />
      </svg>
    </a>
  </li>
</ol>
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
