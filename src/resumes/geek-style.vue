<template>
<div class="resume" id="template">
  <h1>This is a template</h1>
</div>
</template>

<script>
import Vue from 'vue';
import { getVueOptions } from './options';

let name = 'geek-style'; // TODO change name
export default Vue.component(name, getVueOptions(name));
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
</style>
