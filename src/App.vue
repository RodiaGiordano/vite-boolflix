<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";

export default {
  data() {
    return {};
  },

  components: { AppHeader, AppMain },

  methods: {
    searchWord() {
      console.log("click");
    },
  },
};
</script>

<template>
  <AppHeader />
</template>

<style></style>
