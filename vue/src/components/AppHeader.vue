<template>
  <header>
    <h1>{{ headerName }}</h1>
    <button @click="sendEvent">send</button>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
  props: {
    headerName: String,
  },
  methods: {
    sendEvent: function () {
      this.$emit("renew");
    },
  },
};
</script>

<style lang="scss" scoped></style>
