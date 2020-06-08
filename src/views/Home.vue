<template>
  <div class="home">
    <MyHome />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import MyHome from '@/components/home/index.vue';

@Component({
  components: {
    HelloWorld,
    MyHome,
  },
})
export default class Home extends Vue {}
</script>
