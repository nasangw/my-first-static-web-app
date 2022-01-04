<template>
  <div>
    <p>Hello {{ value }}</p>
    <p>I am {{ value2 }}</p>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World",
      value2: "Iron man",
    };
  }
};
</script>
