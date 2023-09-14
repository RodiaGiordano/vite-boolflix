<script>
import CardList from "./CardList.vue";
import SearchBar from "./SearchBar.vue";

export default {
  data() {
    return {
      title: "Hello world",
    };
  },

  components: { CardList, SearchBar },
};
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style lang="scss" scoped></style>
