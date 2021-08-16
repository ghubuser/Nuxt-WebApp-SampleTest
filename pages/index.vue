<template>
  <Tutorial />
</template>

<script>
export default {
  mounted() {
    const text = "sample";
    this.test(text);
  },
  methods: {
    test(text) {
      console.log("test", text);
    },
  },  
};
</script>

<style scoped>
</style>