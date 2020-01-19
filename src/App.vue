<template>
  <div class="box">
    {{ msg }}
  </div>
</template>
<script>
export default {
  data() {
    return {
      msg: 123,
    }
  },
}
</script>
<style lang="less">
.box {
  width: 100px;
  height: 100px;
  background-color: #cdc;
}
</style>
