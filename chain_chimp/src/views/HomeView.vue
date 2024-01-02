<template>
  <div id="home">
    <Navigation/>
    <HeroArea/>
    <Expertise/>
    <Services/>
    <Roadmap/>
    <ChimpTeam/>
    <Partners/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Navigation from '@/components/Navigation.vue'
import HeroArea from '@/components/HeroArea.vue'
import Expertise from '@/components/Expertise.vue'
import Services from '@/components/Services.vue'
import Roadmap from '@/components/Roadmap.vue'
import ChimpTeam from '@/components/ChimpTeam.vue'
import Partners from '@/components/Partners.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Navigation,
    HeroArea,
    Expertise,
    Services,
    Roadmap,
    ChimpTeam,
    Partners,
    Footer
  },
}
</script>

<style scoped>

* {
  margin: 0;
}

#home {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #1E1E1E;
  overflow: hidden;
}


</style>
