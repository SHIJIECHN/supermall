<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <div slot="item-icon"><img src="~assets/img/tabbar/home.svg" alt=""></div>
      <div slot="item-icon-active"><img src="~assets/img/tabbar/home_active.svg" alt=""></div>
      <div slot="item-name">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <div slot="item-icon"><img src="~assets/img/tabbar/category.svg" alt=""></div>
      <div slot="item-icon-active"><img src="~assets/img/tabbar/category_active.svg" alt=""></div>
      <div slot="item-name">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="blue">
      <div slot="item-icon"><img src="~assets/img/tabbar/shopcart.svg" alt=""></div>
      <div slot="item-icon-active"><img src="~assets/img/tabbar/shopcart_active.svg" alt=""></div>
      <div slot="item-name">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="profile" activeColor="blue">
      <div slot="item-icon"><img src="~assets/img/tabbar/profile.svg" alt=""></div>
      <div slot="item-icon-active"><img src="~assets/img/tabbar/profile_active.svg" alt=""></div>
      <div slot="item-name">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import tabBar from 'components/common/tabbar/TabBar'
  import tabBarItem from 'components/common/tabbar/TabBarItem'

  export default {
    name: "mainTabBar",
    components:{
      tabBar, tabBarItem
    }
  }
</script>

<style scoped>

</style>
