<template>
    <header>

        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <a href="#">
                    <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
                </a>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Characters</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Comics</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Movies</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">tv</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">games</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">collectibles</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">videos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">fans</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">news</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">shop</a>
                    </li>

                </ul>
            </div>
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