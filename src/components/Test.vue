<template>
  <div class="test">
    <h2>Hello {{ name }}</h2>
    <ul>
      <li>age: {{ age }}</li>
      <li>colour: {{ color }}</li>
      <li>treat: {{ treat }}</li>
    </ul>
    <p>{{ content }}</p>
  </div>
</template>

<script>
export default {
  props: ["treat"],
  data: function() {
    return {
      name: "test",
      age: 6,
      color: "gray",
      content: "This is test code"
    };
  }
};
</script>

<style lang="scss">
.test h2 {
  color: red;
}
</style>