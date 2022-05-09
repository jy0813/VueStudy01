<template>
  <header>
    <h1>{{ headerName }}</h1>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  props: {
    headerName: String,
  },
};
</script>

<style lang="scss" scoped></style>
