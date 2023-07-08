<script>
export default {
    props: { cards: Array }
};
</script>


<template>
    <ul>
        <li v-for="card in cards" :key="card.series" class="card">
            <div class="thumb">
                <img :src="card.thumb" :alt="card.series">
            </div>
            <div class="description">
                <div class="title">{{ card.title }}</div>
                <div class="type">{{ card.type }}</div>
                <div class="prince">{{ card.price }}</div>
            </div>

        </li>
    </ul>
</template>


<style lang="scss" scoped>
/* style CSS qui*/
ul {
    display: flex;
    flex-wrap: wrap;
}

li {
    flex-basis: calc(100% / 6);
    padding: 10px;
}

li img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.thumb {
    height: 280px;
}

.description {
    color: white;
    display: inline-block;
    margin-top: 10px;
}

.title {
    font-weight: 700;
    text-transform: uppercase;
    margin-bottom: 6px;
}

.type {
    font-weight: 300;
    margin-bottom: 6px;
    text-transform: capitalize
}

.prince {
    font-weight: 900;
    margin-bottom: 6px;
    color: #0282f9;
    font-size: 1.3rem;
}

.load_more {
    background-color: #0282f9;
    color: white;
    display: inline-block;
    padding: 10px 20px;
    font-weight: 600;
}

.load_more:hover {
    background-color: #303030;
    color: white;
    cursor: pointer;
}

.footer {
    text-align: center;
    height: 80px;
    margin-top: 20px;
}
</style>