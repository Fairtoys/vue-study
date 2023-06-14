<template>
    <van-tabbar route  v-model="active" active-color="#1989fa">
        <van-tabbar-item to="home" icon="home-o">首页</van-tabbar-item>
        <van-tabbar-item to="category" icon="search">分类</van-tabbar-item>
        <van-tabbar-item to="cart" icon="search">购物车</van-tabbar-item>
        <van-tabbar-item to="user" icon="search">我的</van-tabbar-item>
    </van-tabbar>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {
    const active = ref(0);
    return { active };
  },
};

</script>

<!-- <style lang="less" scoped>
    @import '../common/style/mixin';


</style> -->



