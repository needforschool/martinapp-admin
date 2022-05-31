<template>
  <main class="app">
    <div class="app__content">
      <transition name="fade">
        <Nuxt />
      </transition>
    </div>
  </main>
</template>

<script>
export default {}
</script>

<style lang="scss">
.app {
  width: 100%;
  min-height: 100vh;
  background: $app-bg-color;
  color: $light;

  &__content {
    margin: 0 auto;
    width: 100%;
    max-width: $width-app;
  }
}

.slide-enter-active,
.slide-leave-active {
  transition: all 0.5s;
}
.slide-enter,
.slide-leave-to {
  opacity: 0;
}
</style>
