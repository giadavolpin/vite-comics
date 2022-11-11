<template>
    <footer>
        <div class="bordoazzur uppercase">
            sing-up now!
        </div>
        <div class="uppercase azzur">follow us</div>
        <ul>
            <li>
                <link rel="stylesheet" href="comics\vue-dc-comics-1\img\footer-facebook.png">
            </li>
            <li>
                <link rel="stylesheet" href="comics\vue-dc-comics-1\img\footer-twitter.png">
            </li>
            <li></li>
            <li></li>
            <li></li>
        </ul>
    </footer>


</template>

<script>
export default {
    name: 'footerComponent'
}
</script>

<style lang="scss" scoped>
footer {
    background-color: rgb(48, 48, 48);
}

.uppercase {
    text-transform: uppercase;
}

.bordoazzur {
    border: 1px solid $azzurro;
}

.azzur {
    color: rgb(2, 130, 249);
}
</style>