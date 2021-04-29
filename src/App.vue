<template>
  <div id="app">
    
    <Nav />

    <Home />

    <About />

    <Skills />

    <Work />

    <Contact />

    <Footer />


  </div>
</template>

<script>
import Nav from './components/NavCard.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Work from './components/Work.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    Nav,
    Home,
    About,
    Skills,
    Work,
    Contact,
    Footer
  },
  
}
</script>

