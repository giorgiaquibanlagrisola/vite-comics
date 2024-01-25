<script>
export default {
  data() {
    return {  }
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

</style>
