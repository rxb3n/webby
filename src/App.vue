<template>

<NavView/>
<HeroView/>
<DescriptionView/>
<ServicesView/>
<ReviewView/>
<ClientView/>
<FooterView/>

</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import DescriptionView from './components/DescriptionView.vue'
import ServicesView from './components/ServicesView.vue'
import ReviewView from './components/ReviewView.vue'
import ClientView from './components/ClientView.vue'
import FooterView from './components/FooterView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    DescriptionView,
    ServicesView,
    ReviewView,
    ClientView,
    FooterView,
  }
}
</script>

<style>

body, h1, h2, h3, h4, h5, h6{
  margin: 0;
  padding: 0;
}

</style>
