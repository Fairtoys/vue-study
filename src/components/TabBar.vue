<template>
    <van-tabbar v-model="active" active-color="#1989fa">
        <van-tabbar-item to="home" icon="home-o">首页</van-tabbar-item>
        <van-tabbar-item to="category" icon="apps-o">分类</van-tabbar-item>
        <van-tabbar-item to="cart" icon="cart-o">购物车</van-tabbar-item>
        <van-tabbar-item to="user" icon="user-o">我的</van-tabbar-item>
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



