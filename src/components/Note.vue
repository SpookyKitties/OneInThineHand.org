<template></template>
<style lang='scss' scoped>
</style>
<script lang='ts'>
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component
export default class Note extends Vue {
  public test() {
    alert('asdofij');
  }
}
Vue.component('note', Note);
</script>

