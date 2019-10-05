<template>
    <van-search
        v-model="value"
        placeholder="输入关键字"
        shape="round"
        show-action
        @search="value"
        left-icon="resPic.mi"
    >
        <div slot="action">搜索</div>
    </van-search>
</template>

<script>
export default {
    name: 'ToBar',
    data(){
        return{
            resPic:{
                mi: require('@/assets/mi.png')
            }
        }
    },
    methods:{

    }

}
</script>

<style>

</style>