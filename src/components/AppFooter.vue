<script>
export default {
    // logica javascript qui
    data() {
        return {
        }
    }
} 
</script>


<template>
    <!-- HTML qui -->
    <!-- LOGHI -->
    <div id="loghi">
        <div>
            <div class="loghi-items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
                <p>DIGITAL COMICS</p>
            </div>
        </div>
        <div>
            <div class="loghi-items">
                <img src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise">
                <p>DC MERCANDISE</p>
            </div>
        </div>
        <div>
            <div class="loghi-items">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
                <p>SUBSCRIPTION</p>
            </div>
        </div>
        <div>
            <div class="loghi-items">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator">
                <p>COMIC SHOP LOCATOR</p>
            </div>
        </div>
        <div>
            <!-- POWER VISA era in SWG.... forse era stato fatto a posta per uamentare la difficolta
            ma io sono un grafico :) e me lo sono cambiato -->
            <div class="loghi-items">
                <img src="../assets/img/buy-dc-power-visa.png" alt="DC Power Visa">
                <p>DC POWER VISA</p>
            </div>
        </div>
    </div>
    <!-- SHORT MENU -->
    <div class="short-menu">
        <div class="container short-menu-bg">
            <!-- DC COMICS --><!-- SHOP MENU -->
            <div class="short-link">

                <div>
                    <ul id="DC-COMICS">
                        <li>
                            <h3>DS COMIC</h3>
                        </li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Video</li>
                        <li>News</li>
                    </ul>
                    <ul id="SHOP">
                        <li>
                            <h3>SHOP</h3>
                        </li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                </div>
                <!-- SHORT DC -->
                <div class="short-link">
                    <ul id="DC">
                        <li>
                            <h3>DC</h3>
                        </li>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>alent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Retings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <!-- SHORT SITE -->
                <div class="short-link">
                    <ul id="SITES">
                        <li>
                            <h3>SITE</h3>
                        </li>
                        <li>DC</li>
                        <li>MAD Magazione</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power visa</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <!-- FOOTER -->
    <div class="footer">
        <div class="container">
            <div class="footer-bottom">
                <div>
                    <a>SIGN-UO NOW!</a>
                </div>
                <!-- SOCIAL -->
                <div class="footer-bottom-left">
                    <div><span>FOLLOW US</span></div>
                    <div><img src="../assets/img/footer-facebook.png" alt="facebook"></div>
                    <div><img src="../assets/img/footer-twitter.png" alt="twitter"></div>
                    <div><img src="../assets/img/footer-youtube.png" alt="youtube"></div>
                    <div><img src="../assets/img/footer-pinterest.png" alt="pintarest"></div>
                    <div><img src="../assets/img/footer-periscope.png" alt="fperiscope"></div>
                </div>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
/* style CSS qui*/
#loghi {
    background-color: #0282f9;
    height: 150px;
    display: flex;
    justify-content: center;
    align-content: center;
    align-items: center;
}

#loghi img {
    display: block;
    height: 50px;
}

#loghi .loghi-items {
    display: flex;
    justify-content: space-between;
    align-content: center;
    align-items: center;
    color: white;
}

#loghi .loghi-items img {
    padding: 0 12px;
}

.short-menu {
    background-color: #303030;
    color: #959595;
    height: 400px;
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.short-menu-bg {
    height: 100%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right;
}

.short-menu h3 {
    margin-bottom: 10px;
    margin-top: 20px;
}

.short-link {
    display: flex;
    justify-content: start;
    align-content: start;
    align-items: start;
    margin: 0px 40px;
}

.footer {
    background-color: #303030;
    height: 100px;
    padding: 20px 0;
    display: flex;
    justify-content: space-between;
    align-content: center;
    align-items: center;
}


.footer a {
    display: inline-block;
    border: solid 2px #0282f9;
    padding: 10px 20px;
    color: white;
}

.footer a:hover {
    display: inline-block;
    border: solid 2px #0282f9;
    background-color: #0282f9;
    padding: 10px 20px;
    color: white;
}

.footer-bottom {
    display: flex;
    align-content: center;
    align-items: center;
    justify-content: space-between;
}

.footer-bottom-left {
    display: flex;
    align-content: center;
    align-items: center;
    color: #0282f9;
}

.footer-bottom-left span {
    margin-right: 20px;
}

.footer-bottom-left img {
    padding: 0 14px;
}
</style>