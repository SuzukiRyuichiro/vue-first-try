<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    title: {
      type: String,
      default: 'Hello world',
    },
  },
};

</script>
<style scoped>
header {
  display: flex;
}

</style>
