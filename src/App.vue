<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return {

     }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
}
</script>

<template>
    <header>
        <div>
            <img src="/img/dc-logo.png" alt="DC-Logo">
        </div>
        <ul>
            <li>
                <a href="#">
                    CHARACTERS
                </a>
            </li>
            <li>
                <a class="active" href="#">
                    COMICS
                </a>
            </li>
            <li>
                <a href="#">
                    MOVIES
                </a>
            </li>
            <li>
                <a href="#">
                    TV
                </a>
            </li>
            <li>
                <a href="#">
                    GAMES
                </a>
            </li>
            <li>
                <a href="#">
                    COLLECTIBLES
                </a>
            </li>
            <li>
                <a href="#">
                    VIDEOS
                </a>
            </li>
            <li>
                <a href="#">
                    FANS
                </a>
            </li>
            <li>
                <a href="#">
                    NEWS
                </a>
            </li>
            <li>
                <a href="#">
                    SHOP
                </a>
            </li>
        </ul>
    </header>

    <main>
        <div class="comics-container">
        -> Content goes here 
        </div>
    </main>

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
    </footer>
</template>

<style lang="scss" scoped>
header {
    display: flex;
    justify-content: space-between;
    padding: 5px;


    > ul {
        display: flex;
        align-items: center;
        list-style: none;

        > li {
            padding: 5px;
            margin-left: 8px;
            margin-right: 8px;

            > a {
                color: black;
                font-weight: bold;
                text-decoration: none;

                &:hover,
                &.active {
                    color: #0C7CEC;
                }
            }
        }

            
    }
}

main {
    .comics-container {
        color: white;
        background-color: black;
        padding: 50px 20px;
        font-weight: bold;
    }
}

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
</style>
