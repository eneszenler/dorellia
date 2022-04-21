<template>
  <div class="top-menu">
    <div class="d-flex justify-content-center align-items-center">
      <nuxt-link to="/">Starters</nuxt-link>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/lunch">Lunch</nuxt-link>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/desserts">Desserts</nuxt-link>
      <span class="dot ms-4 me-4"><i class="bi bi-circle-fill"></i></span>
      <nuxt-link to="/yourorder"
        >Your Order <i class="bi bi-bag"></i> (0)</nuxt-link
      >
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.top-menu {
  margin: 42px auto;
  .golden-lines {
    border-bottom: 1px solid #cf9b38;
    &::after {
      display: block;
      content: '';
      height: 1px;
      width: 80%;
      background-color: #cf9b38;
      position: relative;
      top: 8px;
      margin: 0px auto;
    }
  }
  a {
    color: #495057;
    text-transform: uppercase;
    font-size: 22px;
    font-weight: 300;
    text-decoration: none;
    border-bottom: 1px solid transparent;
    &::after {
      display: block;
      content: '';
      height: 1px;
      background-color: transparent;
    }
    &.nuxt-link-exact-active {
      @extend .golden-lines;
    }
    &:hover {
      @extend .golden-lines;
    }
  }
  .dot {
    display: inline-block;
    color: #cf9b38;
    font-size: 8px;
  }
}
</style>
