<template>
  <main>
    <transition name="fade">
      <Nuxt />
    </transition>
  </main>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.slide-enter-active,
.slide-leave-active {
  transition: all 0.5s;
}
.slide-enter,
.slide-leave-to {
  opacity: 0;
}
</style>
