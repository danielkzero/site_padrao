<template>
  <CabecalhoPrincipal></CabecalhoPrincipal>
  <CabecalhoSecundario></CabecalhoSecundario>
  <main>
    <SliderPrincipal></SliderPrincipal>
    <!--<CartaoPersonalizado></CartaoPersonalizado>-->
    <NossosServicos></NossosServicos>
    <GoogleMapa></GoogleMapa>
    <RodapeSite></RodapeSite>    
  </main>
</template>
<script>

import CabecalhoPrincipal from './components/CabecalhoPrincipal.vue';
import CabecalhoSecundario from './components/CabecalhoSecundario.vue';
import SliderPrincipal from './components/SliderPrincipal.vue';
//import CartaoPersonalizado from './components/CartaoPersonalizado.vue';
import NossosServicos from './components/NossosServicos.vue';
import GoogleMapa from './components/GoogleMapa.vue';
import RodapeSite from './components/RodapeSite.vue';
export default {
  components: {
    //CartaoPersonalizado,
    CabecalhoPrincipal,
    CabecalhoSecundario,
    SliderPrincipal,
    NossosServicos,
    GoogleMapa,
    RodapeSite
  }
}
</script>

<style>

</style>
