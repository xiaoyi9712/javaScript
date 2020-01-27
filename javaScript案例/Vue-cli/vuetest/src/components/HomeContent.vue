<template>
    <div class="content">
        <films-list></films-list>
        <page></page>
    </div>
</template>

<script>
import FilmsList from'@/components/FilmsList'
import Page from'@/components/Page'
    export default {
        data(){
            return {

            }

        },
        components:{
            FilmsList,
            Page
        }
    }
</script>

<style scoped>
    .content{
        width:1200px;
        margin:auto;
        background-color:lightblue;
    }
</style>