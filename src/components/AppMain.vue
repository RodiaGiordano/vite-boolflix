<script>
import CardList from "./CardList.vue";

export default {
  data() {
    return {
      title: "Hello world",
    };
  },

  components: { CardList },
};
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style lang="scss" scoped></style>
