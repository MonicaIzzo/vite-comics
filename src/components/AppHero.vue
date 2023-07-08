<script>
export default {
    // logica javascript qui
    data() {
        return {
            title: 'Hero'
        }
    }
} 
</script>


<template>
    <!-- HTML qui -->
    <div id="hero">
        <div class="title-hero container">
            <!-- <h2>--&gt; Content goes here &lt;--</h2> -->
            <div class="section">CURRENT SERIES</div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
/* style CSS qui*/
/* #hero {
    background-color: black;
    height: 100px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}*/
#hero {
    background-color: #f04997;
    height: 300px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;

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

.section {
    color: white;
    padding: 10px 20px;
    background-color: #0282f9;
    width: 200px;
    font-weight: 900;
    position: absolute;
    top: 280px
}
</style>