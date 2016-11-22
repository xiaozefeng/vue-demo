<template>
    <div>
        <h3>Hello Vue</h3>
    </div>
    <my-menu></my-menu>
</template>
<style>

</style>
<script>
    import Menu from './components/Menu.vue'

    export default{
        data:function(){
            return {
                msg:'我是menu'
            };
        },
        components:{
            'my-menu':Menu
        }
    }
</script>
