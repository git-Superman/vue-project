<template>
<div>
    <img src="@/assets/img/logo.png" alt="">
    <div>
        <h6>hello world</h6>
    </div>
</div>
</template>
<style scoped lang="less" >
    div{
        h6{
            color:@color-red;
            // font-size:@size-24;
        }
    }
</style>
<script>
export default {
    data(){
        return {}
    },
    created(){
        // this.axios.post('http://hh.gualaoshi.com/WxHome/GetCollectionListById?token=123').then(res=>{
        //     console.log(res);
        // });
        this.$store.commit('increment',1000);

        console.log(this.$store.state.count);
    }
}
</script>