<script>
export default {
  data() {
    return {
      title: "Hello world",
    };
  },
};
</script>

<template>
  <div class="input-group flex-nowrap w-50 mx-auto">
    <input
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
