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
    <div class="card_x">
        <div class="img_container">
            <img :src="urlImg" :alt="title">
        </div>
        <div class="text_container">
            <p>{{ title }}</p>
            <p>{{ price }}</p>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.card_x {
    width: calc((100% / 6) - 1rem);
    margin: 2.5rem .5rem;
    border: none;

    .img_container {
        width: 100%;
        height: 100%;
        aspect-ratio: 1 / 1;

        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    }
}

.text_container {
    color: rgb(255, 255, 255);
    font-size: .9em;
    text-align: center;
}
</style>