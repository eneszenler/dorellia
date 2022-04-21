<template>
  <div class="page-title">
    <div class="d-flex justify-content-center align-items-center">
      <div class="left-ornament flex-grow-1"></div>
      <h1>{{ pageTitle }}</h1>
      <div class="right-ornament flex-grow-1"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['pageTitle'],
}
</script>

<style lang="scss">
.page-title {
  h1 {
    font-size: 3.222em;
    padding: 0px 32px;
  }
}
</style>
