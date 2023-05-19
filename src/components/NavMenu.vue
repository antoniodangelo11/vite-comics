<script>
export default {
    props: {
        title: String,
        link: String,
    },
};
</script>

<template>
    <li>
        {{ title }}
    </li>
</template>

<style lang="scss" scoped>
li {
    font-size: .7rem;
    font-weight: bold;
    padding-inline: .5rem;
}

li::after {
    content: "";
    display: block;
    width: 50px;
    height: 5px;
    background-color: #0282f9;
    position: absolute;
    top: 71px;
    left: 49px;
}
</style>