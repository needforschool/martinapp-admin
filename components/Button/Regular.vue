<template>
  <button :class="`button-regular button-regular--${theme}`">
    {{ text }}
  </button>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: "Cliquez ici",
    },
    theme: {
      type: String,
      default: "clasic",
    },
  },
}
</script>

<style lang="scss" scoped>
.button-regular {
  padding: $pad-xs $pad-s;
  border-radius: $rad;
  border: none;
  cursor: pointer;
  font-weight: 700;
  min-width: 215px;

  &:focus,
  &:active {
    border: none;
    outline: none;
  }

  &--clasic {
    background-color: $purple;
    color: $light;
  }
}
</style>
