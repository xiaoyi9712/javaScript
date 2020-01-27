<template>
    <div class="page">
        <ul>
            <li>
                <router-link to="{path:'/',query:{page:1}}">1</router-link>
            </li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
            <li>5</li>
        </ul>
    </div>
</template>

<script>
    export default {}
</script>

<style scoped>
    ul,li{
        list-style:none;
    }
    ul{
        width:320px;
        height:50px;
        margin:auto;
    }
    ul>li{
        float: left;
        width:50px;
        height:45px;
        margin:0 5px;
        border:1px solid rgb(121, 42, 42);
        text-align: center;
        line-height:45px;
        background-color: #ccc;
    }
</style>