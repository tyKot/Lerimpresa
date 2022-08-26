<template>
  <HeaderBlock/>
  <MainBlock/>
</template>

<script>
import HeaderBlock from './components/HeaderBlock.vue'
import MainBlock from './components/MainBlock.vue'

export default {
  name: 'App',
  components: {
    HeaderBlock,
    MainBlock
  }
}
</script>

<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Montserrat',Arial, Helvetica, sans-serif;
  outline: none;
}
body{
  padding: 32px;
}
a{
  text-decoration: none;
  color: #000;
}
</style>
