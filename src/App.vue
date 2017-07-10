<template>
<div id="app">
  <router-view></router-view>
  <ul>
    <router-link tag="li" to="/">外卖</router-link>
    <router-link tag="li" to="/market/Hot">发现</router-link>
    <router-link tag="li" to="/cart">订单</router-link>
    <router-link tag="li" to="/mine">我的</router-link>
  </ul>
</div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      name:'liyongxuan',
      className:'1705'
    }
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
ul{
  width: 100%;
  height: 7rem;
  display: flex;
  justify-content:space-around;
  align-items: center;
  font-size: 3rem;
  position: fixed;
  bottom: 0;
  background-color: #ccc;
  list-style: none;
  text-align: center;
}
</style>
