<template>
  <div id="app">
    <Header></Header>
    <div style="display:flex;flex:1">
      <Left></Left>
      <Right></Right>
    </div>
  </div>
</template>
<style>
  *{
    padding: 0;
    margin: 0;
    outline: none;
    list-style: none;
  }
  #app{
    height: 100vh;
    display: flex;
    flex-direction: column;
  }
</style>
<script>
import Header from './components/Header'
import Left from './components/Left'
import Right from './components/Right'
export default {
  components:{
    Header,
    Left,
    Right
  }
}
</script>
