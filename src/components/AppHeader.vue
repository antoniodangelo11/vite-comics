<script>
import NavMenu from './NavMenu.vue';

export default {
    data() {
        return {
            arrMenu: [
                {
                    "title": "CHARACTERS",
                    "link": "#",
                },
                {
                    "title": "COMICS",
                    "link": "#",
                },
                {
                    "title": "MOVIES",
                    "link": "#",
                },
                {
                    "title": "TV",
                    "link": "#",
                },
                {
                    "title": "GAMES",
                    "link": "#",
                },
                {
                    "title": "COLLECTIBLES",
                    "link": "#",
                },
                {
                    "title": "VIDEOS",
                    "link": "#",
                },
                {
                    "title": "FANS",
                    "link": "#",
                },
                {
                    "title": "NEWS",
                    "link": "#",
                },
                {
                    "title": "SHOP",
                    "link": "#",
                }
            ],
        };
    },
    components: {
        NavMenu,
    }
}
</script>

<template>
    <header>
        <div class="container">
            <img class="logo" src="../assets/img/dc-logo.png" alt="">
            <ul>
                <NavMenu v-for="element in arrMenu" :key="element.title" :title="element.title" :link="element.link" />
            </ul>
        </div>
    </header>
    <div class="jumbotron"></div>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

header {
    background-color: rgb(255, 255, 255);
}

.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: auto;
    max-width: 1200px;
    height: 120px;
}

ul {
    list-style: none;
    align-items: center;
    display: flex;
    gap: 1rem;
    color: rgb(0, 0, 0);
}

.logo {
    height: 80px;
}

.jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    height: 25rem;
}
</style>
