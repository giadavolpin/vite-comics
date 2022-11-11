<template>
    <header>
        <a href="#">
            <img src="../vue-dc-comics-1/img/dc-logo.png" alt="">
        </a>
        <nav>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>

        </nav>
    </header>
</template>

<script>
export default {
    name: 'headerComponent',
    data() {
        return {}
    }
}
</script>

<style lang="scss" scoped>
header {
    background-color: white;
    color: black;
    height: 70px;
}

header img {
    width: 50px;
    height: 50px;
}
</style>