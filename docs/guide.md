# Demo

<vuep template="#example"></vuep>

<script v-pre type="text/x-template" id="example">
<style>
    main{
        width: 100%;
    }
    div{
        width: 229px; height: 139px;
        margin: auto;
        color: #f4f0ea;
        padding: 16px 29px 28px 20px;
        background: #b4a078 url('static/player_logo@2x.png') no-repeat bottom right / 78px 21px;
    }
    .block1{
        background-position: right 29px bottom 28px;
    }
    .block1:hover{
        background-color: red;
        cursor: pointer;
    }
</style>

<template>
    <main>
        <div class="block1">background-position scheme</div>
        <button @click="open()">按鈕 {{name}}</button>
    </main>
</template>

<script>
    module.exports={
        data(){
            return {
                name:"sdadasads"
            }
        },
        methods:{
            open(){
                $.gbox.open(2131);
            }
        }
    }
</script>
</script>
