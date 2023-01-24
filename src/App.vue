<template>
  <NavbarComponent />
  <Featureone />
  <feature-two />
  <featurethree />
  <footer-component />
</template>

<script>
import Featureone from './components/Featureone.vue';
import Featurethree from './components/Featurethree.vue';
import FeatureTwo from './components/FeatureTwo.vue';
import FooterComponent from './components/FooterComponent.vue';
import NavbarComponent from './components/NavbarComponent.vue';



export default {
  name: 'App',
  components: {
    NavbarComponent,
    Featureone,
    FeatureTwo,
    FooterComponent,
    Featurethree
}
}
</script>

<style>

</style>
