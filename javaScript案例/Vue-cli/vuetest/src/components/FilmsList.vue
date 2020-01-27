<template>
    <div class="filmlist">
        <ul>
            <li>
                <img src="https://dss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=2975901083,2518363767&fm=58" alt="">
                <p>{{this.name}}</p>
                <p>{{this.type}}</p>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                src:"https://dss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=2975901083,2518363767&fm=58",
                name:"片名:少年的你",
                type:"剧情 爱情",
                da:{
                src:"https://dss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=2975901083,2518363767&fm=58",
                starring:"周冬雨 易烊千玺",
                type:"剧情 爱情",
                }
            }
        },
    }
</script>

<style scoped>
</style>