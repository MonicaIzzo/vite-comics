/*
Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti necessari per strutturare il layout come da screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.

Diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass!
PS: I font utilizzati sono Open Sans e Open Sans Condensed

Regole:
- Creiamo almeno 3 componenti per la macro struttura (AppHeader, AppMain e AppFooter)
- Per lo stile, installiamo e utilizziamo Sass
- Usare Bootstrap (anche importandolo via CDN) è vietato :P

Bonus:
- Creare un componente aggiuntivo per gestire la fascia azzurra con le icone.
- Importare il font utilizzando Fontsource
*/

<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'Applicazione VITE COMICS',
  components: { AppHeader, AppHero, AppMain, AppFooter },
  data() {
    return {}
  }

} 
</script>


<template>
  <AppHeader />
  <AppHero />
  <AppMain />
  <AppFooter />
</template>

<style>
/* Reset CSS */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Custom PROPERTIES */
:root {
  --primary-color: #0282f9;
  --secondart-color: #1c1c1c;
  --fotter: #303030;
  --bg-social: #797979;
}

/* Generics */
img {
  display: block;
  max-width: 100%;
}

.container {
  width: 1200px;
  margin: 0 auto;
}

/********************************************
    UTILITIES
********************************************/

.debug {
  border: 2px dotted red;
}

/********************************************
    LAYOUT
********************************************/

a {
  color: black;
  text-decoration: none;

}

a:hover {
  color: var(--primary-color)
}

ul {
  list-style: none;
}
</style>