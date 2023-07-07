<script>
// logica javascript qui
import AppCard from './AppCard.vue';
export default {
    components: { AppCard },
    data() {
        return {}
    }
} 
</script>


<template>
    <h1>CARDS</h1>
    <AppCard />
</template>


<style lang="scss" scoped>
/* style CSS qui*/
h1 {
    color: white;
}
</style>