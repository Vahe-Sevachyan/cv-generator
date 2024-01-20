<script>
export default {
  data() {
    return {
      firstName: "",
      displayFirstName: "",
      // lastName: "",
      // displayLastName: "",
    };
  },
  props: {
    firstName: String,
  },
};
</script>

<template>
  <div class="firstName-container">
    <label for="firstName">First Name</label>
    <input type="text" />
    <!-- <span>{{ firstName }}</span> -->
  </div>
  <!-- <div class="lastName-container">
    <label for="lastName">Last Name</label>
    <input type="text" />
    <span>{{ lastName }}</span>
  </div> -->
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
