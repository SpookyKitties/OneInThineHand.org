<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import Test from '@/components/Test.vue';
import BodyBlock from '@/components/BodyBlock.vue';
@Component({
  components: {
    HelloWorld,
    Test,
    BodyBlock,
  },
})
export default class Home extends Vue {}
</script>
