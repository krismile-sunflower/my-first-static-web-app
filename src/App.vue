<template>
  <div>Hello {{ value }} 欢迎来到vue</div>
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
