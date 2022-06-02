<template>
  <div class="login">
    <div class="login--card card">
      <h2>Connexion</h2>
      <form @submit.prevent="login">
        <div class="form-group">
          <label for="email">Email</label>
          <input
            type="email"
            class="form-control"
            id="email"
            v-model="email"
            placeholder="Email"
          />
        </div>
        <div class="form-group">
          <label for="password">Mot de passe</label>
          <input
            type="password"
            class="form-control"
            id="password"
            v-model="password"
            placeholder="Mot de passe"
          />
        </div>
        <ButtonRegular text="Connexion" />
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: "",
      password: "",
    }
  },
  methods: {
    login() {
      console.log(this.email, this.password)
    },
  },
}
</script>

<style lang="scss">
.login {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;

  &--card {
    width: 90%;

    @include min-lg {
      width: 40%;
    }
  }
}
</style>
