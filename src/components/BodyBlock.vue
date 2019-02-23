<template>
  <div>asdf</div>
</template>
<style lang='scss' scoped>
</style>
<script lang='ts'>
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component
export default class BodyBlock extends Vue {
  public test() {
    alert('asdofij');
  }
}
Vue.component('body-block', BodyBlock);
</script>

