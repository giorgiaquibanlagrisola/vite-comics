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
            <img src="../public/img/dc-logo.png" alt="DC-Logo">
        </div>
        <ul>
            <li>
                <a href="#">
                    CHARACTERS
                </a>
            </li>
            <li>
                <a href="#">
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

                &:hover {
                    color: #0C7CEC;
                }
            }
        }

            
    }
}
</style>
