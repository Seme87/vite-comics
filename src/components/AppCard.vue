<script>
export default {
  name: "AppCard",
  props: {
    img: String,
    title: String,
  },
};
</script>

<template>
  <div class="card">
    <img :src="img" alt="" />
    <h3>{{ title }}</h3>
  </div>
</template>

<style lang="scss" scoped>
.card {
  padding: 10px 10px;
  h3 {
    margin-top: 10px;
    text-align: center;
    color: white;
  }
  img {
    max-width: 100%;
  }
}
</style>
