<script></script>

<template>
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

header {
    background-color: rgb(255, 255, 255)
}

nav {
    display: flex;
    justify-content: space-between;
    margin: auto;
    height: 120px;
    max-width: 1200px;
}

ul {
    list-style: none;
    align-items: center;
    gap: 1rem;
    display: flex;
    color: rgb(0, 0, 0);

    li {
        font-size: .7rem;
        font-weight: bold;
        padding-inline: .5rem;
    }
}

img {
    margin-top: 1rem;
    height: 80px;
}
</style>
