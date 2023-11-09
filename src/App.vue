<template>
  <div>
    <h1>Hello {{ value }} 欢迎来到vue3</h1>
    <h1>加油</h1>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
