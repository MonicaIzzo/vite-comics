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
                    <li v-for="link in links" :key="link.text">
                        <a :href="link.url" :class="{ active: link.current }">{{ link.text }}</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>


<style lang="scss" scoped>
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
    position: relative;
    font-weight: bold;
    text-transform: uppercase;
}

li a {
    padding: 10px 20px;

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

li a.active {

    background-color: rgba(2, 130, 250, 1);
    color: white;
}
</style>