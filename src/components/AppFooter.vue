<script>
export default {
  data() {
    return {  }
  },
}
</script>

<template>
  <footer>
        <div class="links-container">
            <div>
                <div class="buy-comics">
                    <img src="/img/buy-comics-digital-comics.png" alt="">
                </div>
                
                <a href="#">
                    DIGITAL COMICS
                </a>
            </div>
            <div>
                <div class="buy-comics">
                    <img src="/img/buy-comics-merchandise.png" alt="">
                </div>
                
                <a href="#">
                    DC MERCHANDISE
                </a>
            </div>
            <div>
                <div class="buy-comics">
                    <img src="/img/buy-comics-subscriptions.png" alt="">
                </div>
                
                <a href="#">
                    SUBSCRIPTIONS
                </a>
            </div>
            <div>
                <div class="buy-comics">
                    <img src="/img/buy-comics-shop-locator.png" alt="">
                </div>
                
                <a href="#">
                    COMIC SHOP LOCATOR
                </a>
            </div>
            <div>
                <div class="buy-comics">
                    <img src="/img/buy-dc-power-visa.svg" alt="">
                </div>
                
                <a href="#">
                    DC POWER VISA
                </a>
            </div>
        </div>
        <div class="main-footer">
            <div class="columns-links-container">
                <div>
                    <h4>
                        DC COMICS 
                    </h4>
                    <ul>
                        <li>
                            <a href="#">
                                Characters
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Comics 
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Movies 
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                TV
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Games
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Videos
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                News
                            </a>                            
                        </li>
                    </ul>
                </div>

                <div>
                    <h4>
                        DC 
                    </h4>
                    <ul>                        
                        <li>
                            <a href="#">
                                Terms Of Use
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Privacy policy (New)
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Ad Choices
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Advertising
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Jobs
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Subscriptions 
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Talent Workshops
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                CPSC Certificates
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Ratings
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Shop Help
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                Contact Us
                            </a>                            
                        </li>
                    </ul>
                </div>

                <div>
                    <h4>
                        SITES
                    </h4>

                    <ul>                        
                        <li>
                            <a href="#">
                                DC
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                MAD Magazine
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                DC Kids
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                DC Universe
                            </a>                            
                        </li>
                        <li>
                            <a href="#">
                                DC Power Visa
                            </a>                            
                        </li>
                    </ul>
                </div>

            </div>
            <div class="footer-logo-container">
                <img src="../public/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="footer-bottom">
            <div>
                <button>
                    SIGN-UP NOW!
                </button>
            </div>

            <div class="social-link-container">
                <h3>
                    FOLLOW US
                </h3>
                <div>
                    <img src="../public/img/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="../public/img/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="../public/img/footer-youtube.png" alt="">
                </div>
                <div>
                    <img src="../public/img/footer-pinterest.png" alt="">
                </div>
                <div>
                    <img src="../public/img/footer-periscope.png" alt="">
                </div>

            </div>
        </div>
    </footer>

</template>

<style lang="scss" scoped>
.links-container {
    display: flex;
    justify-content: space-between;
    background-color: #0C7CEC;
    color: white;
    text-decoration: none;
}
.buy-comics {

}

.main-footer {
    min-height: 400px;
    background-image: url('../public/img/footer-bg.jpg');
    display: flex;
    justify-content: space-between;
    
}

.footer-logo-container {
    width: calc(100% / 2);
}

.columns-links-container {
    display: flex;
}

.footer-bottom {
    display: flex;
    justify-content: space-between;
    height: 100px;
    background-color: #303030;
    align-items: center;
}

.social-link-container {
    display: flex;
    align-items: center;

    > div {
        width: 30px;
        height: 30px;
    }
}

</style>
