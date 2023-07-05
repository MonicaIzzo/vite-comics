<script>
export default {
    // logica javascript qui
    data() {
        return {
            /* text: data.text,
            url: data.url,
            current: data.current */
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ],
        }
    }
} 
</script>


<template>
    <!-- HTML qui -->
    <header>
        <nav class="debug container">
            <div>
                <img class="logo" src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div>
                <ul>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTILES</a></li>
                    <li><a href="#">VIDEO</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </div>
        </nav>
    </header>
</template>


<style scoped>
/* style CSS qui*/

header {
    height: 100px;
    margin: 10px auto;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    width: 80px;
}

ul {
    display: flex;
    justify-content: space-between;
    align-content: center;
    align-items: center;
    list-style-type: none;
}

li {
    list-style: none;
    margin: 0 20px;
    position: relative;
}

li a:hover::after {
    content: "-";
    background-color: #0282f9;
    display: block;
    width: 100%;
    height: 1;
    position: absolute;
    top: 74px;
    left: 0px;
    right: 0px;
    font-size: 4px;

}
</style>