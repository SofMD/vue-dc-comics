<template>

<div>
    <img :src="thumb" :alt="series">
    <div class="t-t-upp text">{{series}}</div>
</div>
    
</template>

<script>
export default {
    name: 'Card',
    props: {
        thumb: String,
        series: String,
    },
};
</script>

<style scoped lang="scss">
div {
    margin: 20px 10px;

    img{
        width: 190px;
        height: 190px;
        object-fit: cover;
        object-position: right top;
    }

    .text{
        width: 190px;
        margin: 5px 0;
    }
}

</style>