<template>
    <div class="background-footer">
        <div class="container">
            <div class="DC-shop">

                <div id="dc-comics-list">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                </div>
                <div id="dc-team">
                    <h4>DC</h4>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact US</a></li>
                    </ul>
                </div>
                <div id="sites">
                    <h4>SITES</h4>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
                <div id="shop">
                    <h4>SHOP</h4>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
            </div>
            <figure>
                <img src="../assets/img/dc-logo-bg.png" alt="logo DC background">
            </figure>
        </div>
    </div>

</template>

<script>
export default {
    name: "TopFooter",
}
</script>

<style scoped>
.background-footer {
    background-image: url('../assets/img/footer-bg.jpg');
    background-position: center;
    background-size: contain;
    height: 300px;
}

.container {
    display: flex;
}

.container .DC-shop {
    display: flex;
    width: 40%;
    flex-wrap: wrap;
}

.container div {
    margin: 0 30px;
    height: 190px;
}

#shop {
    display: block;
}

h4 {
    color: #fff;
}

ul li a {
    font-size: 13px;
}

.container img {
    height: 53%;
    margin-left: 100px;
}
</style>