<template>
  <TitleBlock />
  <FooterBlock />
</template>

<script>
import TitleBlock from './components/TitleBlock.vue';
import FooterBlock from './components/FooterBlock.vue';

export default {
  name: 'App',
  components: {
    TitleBlock,
    FooterBlock
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
