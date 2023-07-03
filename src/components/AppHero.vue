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
        <img src="../assets/img/jumbotron.jpg" alt="Hero">
        <div class="title">CURRENT SERIES</div>
    </div>
</template>


<style scoped>
/* style CSS qui*/
#hero {
    background-color: #f04997;
}

.title {
    background-color: #0282f9;
}
</style>