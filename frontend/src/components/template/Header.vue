<template>
  <div class="header"></div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
.header {
  grid-area: header;
  background-color: linear-gradient(to right, #1e469a, #49a7c1);

  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
