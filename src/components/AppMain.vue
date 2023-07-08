<script>
// logica javascript qui
import AppCards from './Appcards.vue';
export default {
    components: { AppCards },

    data() {
        return {
        }
    }
} 
</script>
<template>
    <div class="main">
        <div id="cards" class="container">
            <AppCards />
            <div class="footer">
                <a class="load_more">LOAD MORE</a>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
/* style CSS qui*/
.main {
    background-color: black;
    padding-top: 50px;
}
</style>