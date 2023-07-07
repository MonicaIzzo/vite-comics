<script>
// logica javascript qui
</script>


<template>
    <ul>
        <li class="card">
            <img src="../assets/img/card.jpg" alt="img 01">
            <div class="description">
                <div class="title">Action Comics</div>
                <div class="type">comic book</div>
                <div class="prince">$19.99</div>
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