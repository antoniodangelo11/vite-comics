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
}
</style>