<template>
    <div>
        <div class="crumbs">
            <el-breadcrumb separator="/">
                <el-breadcrumb-item>
                    <i class="el-icon-setting"></i> 资金股份
                </el-breadcrumb-item>
            </el-breadcrumb>
            <el-card class="container ">
                <posi-list></posi-list>
            </el-card>
        </div>
    </div>
</template>

<script>
    import PosiList from "../components/PosiList"

    export default {
        name: "Dashboard",
        components: {
            PosiList
        }
    }
</script>

<style scoped>

</style>