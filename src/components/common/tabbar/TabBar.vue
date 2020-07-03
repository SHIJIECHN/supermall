<template>
  <div class="tab-bar">
    <slot></slot>
  </div>

</template>

<script>
  import TabBarItem from "./TabBarItem";
  export default {
    name: "TabBar",
    components:{
      TabBarItem
    }
  }
</script>

<style scoped>
  .tab-bar{
    display: flex;
    height: 49px;
    background-color: #66666617;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    border-top: rgba(100,100,100,.08) 2px solid;
  }
</style>
