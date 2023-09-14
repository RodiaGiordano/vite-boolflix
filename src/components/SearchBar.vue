<script>
import { store } from "../store.js";
export default {
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <div class="input-group flex-nowrap w-50 mx-auto">
    <input
      v-model="store.textSearch"
      type="text"
      class="form-control"
      placeholder="Search..."
      aria-label="Search..."
      aria-describedby="addon-wrapping"
    />
    <span class="input-group-text" id="addon-wrapping">Search</span>
  </div>
</template>

<style lang="scss" scoped></style>
