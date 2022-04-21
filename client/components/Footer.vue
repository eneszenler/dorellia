<template>
  <footer class="text-center">
    <Logo />
    <span>Copyright 2022 d'Orellia</span>
    <nuxt-link to="/"> Privacy Policy </nuxt-link>
    <nuxt-link to="/"> Terms of Use </nuxt-link>
    <nuxt-link to="/"> Contact </nuxt-link>
  </footer>
</template>

<script>
export default {}
</script>

<style lang="scss">
footer {
  .logo {
    img {
      max-height: 45px;
    }
  }
}
</style>
