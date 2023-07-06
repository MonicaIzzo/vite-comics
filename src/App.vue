/* MILESTONE 1
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

/* MILESTONE 2
Continuate a lavorare nella stessa repo di ieri e create un nuovo componente che rappresenterà le card dei fumetti.
Utilizzate i dati presenti nel file che trovate in allegato copiandoli nel vostro AppMain e passateli al componente ComicCard tramite props.
Una volta inseriti tutti i contenuti dinamicamente, completate il vostro layout e rifinite i dettagli con Sass.
Bonus:
Far partire i dati dal componente App anziché dal componente AppMain !
*/


<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppCard from './components/AppCard.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'Applicazione VITE COMICS',
  components: { AppHeader, AppHero, AppCard, AppFooter },
  data() {
    return {}
  }
} 
</script>


<template>
  <AppHeader />
  <AppHero />
  <AppCard />
  <AppFooter />
</template>

<style lang="scss">
@use 'assets/scss/style.scss' as *;
</style>