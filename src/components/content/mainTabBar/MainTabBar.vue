<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <div slot="item-icon"><img src="assets/img/home.png" alt=""></div>
      <div slot="item-icon-active"><img src="assets/img/home-active.png" alt=""></div>
      <div slot="item-name">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <div slot="item-icon"><img src="assets/img/category.png" alt=""></div>
      <div slot="item-icon-active"><img src="assets/img/category-active.png" alt=""></div>
      <div slot="item-name">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="blue">
      <div slot="item-icon"><img src="assets/img/cart.png" alt=""></div>
      <div slot="item-icon-active"><img src="assets/img/cart-active.png" alt=""></div>
      <div slot="item-name">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="profile" activeColor="blue">
      <div slot="item-icon"><img src="assets/img/profile.png" alt=""></div>
      <div slot="item-icon-active"><img src="assets/img/profile-active.png" alt=""></div>
      <div slot="item-name">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import tabBar from './tabbar/TabBar'
  import tabBarItem from './tabbar/TabBarItem'

  export default {
    name: "mainTabBar",
    components:{
      tabBar, tabBarItem
    }
  }
</script>

<style scoped>

</style>
