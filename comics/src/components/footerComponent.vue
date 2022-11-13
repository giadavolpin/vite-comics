<template>
    <footer>
        <div class="backg-comic d-flex">
            <div class="d-flex flex-column">
                <ul>
                    <h5 class="uppercase bianco">dc comics</h5>
                    <li class="grigio">Characters</li>
                    <li class="grigio">Comics</li>
                    <li class="grigio">Movies</li>
                    <li class="grigio">TV</li>
                    <li class="grigio">Games</li>
                    <li class="grigio">Videos</li>
                    <li class="grigio">News</li>
                </ul>
                <ul>
                    <h5 class="uppercase bianco">shop</h5>
                    <li class="grigio">Shop DC</li>
                    <li class="grigio">Shop DC Collectibles</li>
                </ul>
            </div>
            <ul>
                <h5 class="uppercase bianco">dc</h5>
                <li class="grigio">Terms Of Use</li>
                <li class="grigio">Privacy policy (New)</li>
                <li class="grigio">Ad Choices</li>
                <li class="grigio">Advertising</li>
                <li class="grigio">Jobs</li>
                <li class="grigio">Subscriptions</li>
                <li class="grigio">Talent Workshops</li>
                <li class="grigio">CPSC Certificates</li>
                <li class="grigio">Ratings</li>
                <li class="grigio">Shop Help</li>
                <li class="grigio">Contact Us</li>
            </ul>
            <ul>
                <h5 class="uppercase bianco">sites</h5>
                <li class="grigio">DC</li>
                <li class="grigio">MAD Magazine</li>
                <li class="grigio">DC Kids</li>
                <li class="grigio">DC Universe</li>
                <li class="grigio">DC Power Visa</li>
            </ul>
            <div>
                <img class="wh" src="../assets/vue-dc-comics-1/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="backg-foolow d-flex justify-content-between">
            <div class="bordoazzur uppercase">
                <!-- centrare con il bordo -->
                sing-up now!
            </div>
            <div class="uppercase azzur d-flex flex-row">
                <p><strong>follow us</strong></p>
                <link rel="stylesheet" href="../assets/vue-dc-comics-1/img/footer-facebook.png">
                <link rel="stylesheet" href="../assets/vue-dc-comics-1/img/footer-twitter.png">
                <link rel="stylesheet" href="../assets/vue-dc-comics-1/img/footer-youtube.png">
                <link rel="stylesheet" href="../assets/vue-dc-comics-1/img/footer-pinterest.png">
                <link rel="stylesheet" href="../assets/vue-dc-comics-1/img/footer-periscope.png">
                <!-- non mi fa vedere le icone  -->
            </div>
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

.backg-foolow {
    background-color: rgb(48, 48, 48);
    height: 100px;
    z-index: 1000;
}

.uppercase {
    text-transform: uppercase;
}

.bordoazzur {
    border: 2px solid rgb(2, 130, 249);
    width: 150px;
    color: white;
}

.azzur {
    color: rgb(2, 130, 249);
}

.grigio {
    color: rgb(121, 121, 121);
    list-style-type: none;
    font-size: 12px;
}

.icone {
    color: rgb(121, 121, 121);
}

.bianco {
    color: white;
}

.wh {
    width: 300px;
    height: 300px;
    /* sistemare qui */
}
</style>