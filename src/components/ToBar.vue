<template>
    <div>
        <van-search
            v-model="value"
            placeholder="输入关键字"
            shape="round"
            show-action
            @search="value"
        >
            <div slot="action">搜索</div>
        </van-search>
        <van-row type="flex">
            <van-col span="4" class="miU">
                <div class="miImg"></div>
            </van-col>
            <van-col span="16">
                <van-search
                    v-model="value"
                    placeholder="输入关键字"
                    shape="round"
                />
            </van-col>
            <van-col span="4">
                <van-button round="true" size="small" style="margin:auto 0;">搜索</van-button>
            </van-col>
        </van-row>
    </div>
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
    .miU{
        padding: 15px; 
    }
    .miImg{
        width: 100%;
        height:100%;
        background-image: url('../assets/mi.png');
        background-repeat: no-repeat;
        background-size: 100% 100%;
        /* 将图片作为背景，占满div */
    }
</style>