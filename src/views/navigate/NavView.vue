<template>
    <div>
        
        <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect"
            background-color="#545c64" text-color="#fff" active-text-color="#ffd04b">
            <el-menu-item index="1">首页</el-menu-item>
            <el-menu-item index="2">搜索地图</el-menu-item>
            <el-menu-item index="3">上传</el-menu-item>
            <el-menu-item index="4">列表</el-menu-item>
        </el-menu>
    </div>
</template>
<script>
export default {

    data() {
        return {
            activeIndex: '1'
        }
    },
    computed: {

    },
    watch: {

    },
    mounted() {

    },
    methods: {
        handleSelect(key, keyPath) {
            console.log(key, keyPath);
      }
    }
};
</script>
<style lang='' scoped>

</style>