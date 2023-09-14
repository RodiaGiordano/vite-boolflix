<script>
import Card from "./Card.vue";

export default {
  data() {
    return {
      title: "Hello world",
    };
  },

  components: { Card },
};
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style lang="scss" scoped></style>
