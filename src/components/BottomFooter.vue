<template>
    <div class="final-footer">
        <div class="container">
            <div class="btn-sign-up">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="follow-us">
                <h4>FOLLOW US</h4>
                <ul>
                    <li><img src="../assets/img/footer-facebook.png" alt="facebook"></li>
                    <li><img src="../assets/img/footer-twitter.png" alt="twitter"></li>
                    <li><img src="../assets/img/footer-youtube.png" alt="youtube"></li>
                    <li><img src="../assets/img/footer-pinterest.png" alt="pinterest"></li>
                    <li><img src="../assets/img/footer-periscope.png" alt="periscope"></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "BottomFooter",
}
</script>

<style scoped>
.final-footer {
    background-color: #303030;
    height: 100px;
}

.container {
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.follow-us {
    display: flex;
}

.follow-us ul {
    display: flex;
}

.follow-us h4 {
    color: #0282f9;
    font-size: 20px;
    font-weight: bold;
    padding: 0 10px;
}

.follow-us li {
    padding: 0 10px;
}

.btn-sign-up button {
    background-color: #303030;
    border: 2px solid #0282f9;
    color: #fff;
    padding: 10px 15px;
}
</style>