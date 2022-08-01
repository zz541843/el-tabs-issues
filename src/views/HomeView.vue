<script setup lang="ts">

</script>

<template>
    <div style="display:flex;">
        在此文件随便加减，触发热更新后报错
        <el-tabs type="border-card" >
            <el-tab-pane
                label="2">
                <div v-for="item in [1,2]"
                >
                    <div style="width: 44px;">
                        <div v-if="item===1">{{ item }}</div>
                        <div v-show="item===1">{{ item }}</div>
                    </div>
                </div>
            </el-tab-pane>
        </el-tabs>
    </div>
</template>

<style lang="scss" scoped>
</style>
