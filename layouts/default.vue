<template>
  <div class="page_layout">
    <Header class="header"/>
    <div class="content">
      <nuxt />
    </div>
  </div>
</template>

<script>
export default {
  components: {
  },
  data() {
    return {
    }
  },
  methods:{
  },
  mounted() {
  }
};
</script>
<style scoped lang='scss'>
.page_layout {
  .header {
    width: 100%;
    height: 50px;
    text-align: center;
    background: gray;
    top: 0px;
  }
  .content {
  }

}
</style>
