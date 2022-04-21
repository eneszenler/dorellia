<template>
  <div class="page-title">
    <h1>{{ pageTitle }}</h1>
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
  }
}
</style>
