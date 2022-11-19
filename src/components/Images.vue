<template>
    <div class="img">
        <img src="https://picsum.photos/100/100/?random=10">
    </div>
</template>
<script>
export default {
    props:{
        link:String
    }
}
</script>
<style lang="scss">
    .img{
        background: #ccc;
        display: inline-flex;
        margin: 10px;
    }
</style>