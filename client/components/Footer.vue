<template>
  <footer class="footer">
    <div class="d-flex justify-content-center align-items-center">
      <div class="left-ornament flex-grow-1"></div>
      <Logo />
      <div class="right-ornament flex-grow-1"></div>
    </div>

    <div class="footer__menu d-flex justify-content-center align-items-center">
      <span>Copyright &copy; 2021 d’Orellia</span>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/">Privacy Policy</nuxt-link>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/">Terms of Use</nuxt-link>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/">Contact</nuxt-link>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style lang="scss">
.footer {
  margin: 72px auto;
  .logo {
    margin: 0px 32px;
    img {
      width: 150px;
    }
  }
  &__menu {
    margin-top: 28px;
  }
  a {
    color: #495057;
    text-decoration: none;
    border-bottom: 1px solid transparent;
    &:hover {
      color: #495057;
      border-bottom: 1px solid #cf9b38;
    }
  }
  .dot {
    display: inline-block;
    color: #cf9b38;
    font-size: 8px;
  }
}
</style>
