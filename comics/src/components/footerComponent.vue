<template>
    <footer>
        <div class="backg-comic">

        </div>
        <div class="">
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
        </div>
    </footer>


</template>

<script>
export default {
    name: 'footerComponent'
}
</script>

<style lang="scss" scoped>
.backg-comic {
    background-image: url(../assets/vue-dc-comics-1/img/footer-bg.jpg);
    height: 270px;
}

/*     {
    background-color: rgb(48, 48, 48);
} */

.uppercase {
    text-transform: uppercase;
}

.bordoazzur {
    border: 1px solid lightblue;
}

.azzur {
    color: rgb(2, 130, 249);
}
</style>