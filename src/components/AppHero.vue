<script>
export default {
    // logica javascript qui
    data() {
        return {
            title: 'Prima applicazione app Vite'
        }
    }
} 
</script>


<template>
    <!-- HTML qui -->
    <div id="hero">
        <div class="title-hero container">
            <h2>--&gt; Content goes here &lt;--</h2>
        </div>
    </div>
</template>


<style scoped>
/* style CSS qui*/
#hero {
    background-color: black;
    height: 100px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

/* #hero {
    background-color: #f04997;
    height: 400px;
    background-image: url('../assets/img/jumbotron.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}*/

.title-hero {
    color: white;
}
</style>