<template>
    <div class="test">
        <h1>{{ title }}</h1>
        <span v-html="titlehtml"></span>
        <p>{{ user.firstName }}</p>
        <p v-text="user.lastName"></p>
    </div>
</template>

<script>
export default {
  name: "test",
  data() {
    return {
      title: "Hello World",
      titlehtml: "<h1>Hello World </h1>",
      user: {
        firstName: "John",
        lastName: "Doe"
      }
    };
  }
};
</script>

<style scoped>

</style>
