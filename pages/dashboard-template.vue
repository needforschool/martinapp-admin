<template>
  <div class="w-full flex">
    <Sidebar />
    <div class="w-10/12">
    
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
