<template>
  <div>
    <button @click="test">test</button>
  </div>
</template>
<style lang="scss" scoped>
</style>
<script lang="ts">
import Vue from 'vue';
import { Component } from 'vue-property-decorator';

@Component
export default class Test extends Vue {
  public test() {
    alert('asdofij');
  }
}
Vue.component('test-test', Test);
</script>

