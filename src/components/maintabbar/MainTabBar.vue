<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="deeppink">
        <img slot="item-icon" src="~assets/img/home.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/home_active.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="deeppink">
        <img slot="item-icon" src="~assets/img/category.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/category_active.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="deeppink">
        <img slot="item-icon" src="~assets/img/shopcart.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/shopcart_active.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="deeppink">
        <img slot="item-icon" src="~assets/img/profile.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/profile_active.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>      
    </tab-bar>
  </div>
</template>

<script>
import TabBar from 'components/tabbar/TabBar'
import TabBarItem from 'components/tabbar/TabBarItem'

  export default {
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style>

</style>