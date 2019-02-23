<template></template>
<style lang='scss' scoped>
</style>
<script lang='ts'>
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component
export default class EditorBlock extends Vue {
  public test() {
    alert('asdofij');
  }
}
Vue.component('editor-block', EditorBlock);
</script>

