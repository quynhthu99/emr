<template>
  <div id="components-back-top-demo-custom">
    <a-back-top v-bind="$attrs">
      <div class="ant-back-top-inner">UP</div>
    </a-back-top>
    Scroll down to see the bottom-right
    <strong style="color: #1088e9">blue</strong>
    button.
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BackTop',
  setup() {
    return {}
  }
})
</script>

<style scoped>
#components-back-top-demo-custom .ant-back-top {
  bottom: 100px;
}
#components-back-top-demo-custom .ant-back-top-inner {
  height: 40px;
  width: 40px;
  line-height: 40px;
  border-radius: 4px;
  background-color: #1088e9;
  color: #fff;
  text-align: center;
  font-size: 20px;
}
</style>
