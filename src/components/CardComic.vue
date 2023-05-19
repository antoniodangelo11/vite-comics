<script>
export default {
    props: {
        urlImg: String,
        title: String,
    },
};
</script>

<template>
    <div class="card">
        <img :src="urlImg" :alt="series">
        <h2>{{ title }}</h2>
    </div>
</template>

<style lang="scss" scoped>
.card {
    max-width: 200px;
    text-align: center;
    border: 2px solid black;
}

img {
    width: 100%;
}
</style>