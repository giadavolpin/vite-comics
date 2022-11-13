<template>
    <p class="nero">
        --> Content goes here </p>

    <div class="azzurro-sfondo uppercase d-flex justify-content-center flex-row align-items-center">

        <img class=" mis-azz m-1" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="">
        <p class=" uppercase m-2">digital comics</p>
        <img class=" mis-azz m-1" src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="">
        <p class=" uppercase m-2">dc merchandise</p>
        <img class=" mis-azz m-1" src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="">
        <p class=" uppercase m-2">subscription</p>
        <img class=" mis-azz m-1" src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="">
        <p class=" uppercase m-2">comic shop locator</p>
        <img class=" mis-azz m-1" src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="">
        <p class=" uppercase m-2">dc power visa</p>

    </div>


</template>

<script>
export default {
    name: 'mainComponent'
}
</script>

<style lang="scss" scoped>
.nero {
    background-color: black;
    height: 70px;
    color: white;
    margin-bottom: 0;
}

.azzurro-sfondo {
    background-color: rgb(2, 130, 249);
    color: white;
    height: 100px;
}

.uppercase {
    text-transform: uppercase;
    font-size: 12px;
}

.mis-azz {
    width: 25px;
    height: 30px;
}
</style>