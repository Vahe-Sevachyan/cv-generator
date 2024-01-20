<template>
  <div class="firstName-container">
    <button @click="displayF_Name">Add First Name</button><br />
    <input type="text" v-model="inputFirstName" />
    <p v-if="displayFirstName">{{ displayFirstName }}</p>
  </div>
  <!-- <div class="lastName-container">
    <label for="lastName">Last Name</label>
    <input type="text" />
    <span>{{ lastName }}</span>
  </div> -->
</template>

<script>
export default {
  data() {
    return {
      inputFirstName: "",
      displayFirstName: "",
      // lastName: "",
      // displayLastName: "",
    };
  },
  // props: {
  //   firstName: String,
  // },
  methods: {
    displayF_Name() {
      this.displayFirstName = this.inputFirstName;
    },
  },
};
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
