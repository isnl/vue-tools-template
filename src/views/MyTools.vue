<template>
  <div class="my-tools">
    <div class="tools-head">头部</div>
    <div class="tools-body">
      <p>{{ msg }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyTools",
  data() {
    return {
      msg: "在此界面完成您的布局、工具实现"
    };
  }
};
</script>

<style lang="less" scoped>
.my-tools {
  width: 100%;
  height: 100%;
  .tools-head {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-bottom: 1px solid #e1e1e1;
  }
  .tools-body {
    width: 1300px;
    margin: 20px auto 0;
    // min-height: 1000px;
    padding: 20px;
    box-sizing: border-box;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
  }
}
</style>
