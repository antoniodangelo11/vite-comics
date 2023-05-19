<script>
export default {
    props: {
        urlImg: String,
        title: String,
        price: String,
    },
};
</script>

<template>
    <div class="card">
        <img :src="urlImg" :alt="title">
        <p>{{ title }}</p>
        <p>{{ price }}</p>
    </div>
</template>

<style lang="scss" scoped>
.card {
    width: 15%;
    background-color: transparent;
    border: none;

    img {
        width: 100%;
    }

    p {
        color: white;
    }
}
</style>