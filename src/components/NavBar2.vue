<template>
    <div>

    </div>
</template>

<script>
</script>

<style lang="less" scoped>
@import '../common/style/mixin.less';

.nav-bar {
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: aliceblue;

    .nav-list {
        width: 100%;
        display: flex;
        flex-direction: row;

        .nav-list-item {
            display: flex;
            flex-direction: column;
            flex: 1;
        }
    }

}
</style>