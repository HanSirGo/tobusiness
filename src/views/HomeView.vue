<template>
  <div class="home">
    <h3>hello</h3>
    <el-button type="primary" class="btn">Primary</el-button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>
<style lang="scss" scoped>
.home{
  --button-bk-color:#f00;
  h3{
    color:red;
  }
  .btn{
    background: var(--button-bk-color);
  }
}
</style>