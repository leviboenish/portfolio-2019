<template>
  <div class="container">
    <Nav />
    <img src="../assets/me.jpg" alt="">
    <h1 class="title">
      Levi Boenish
    </h1>
    <h1 class="about-index main-index">00.</h1>
    <About />
    <Skills />
    <Experience />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import About from '~/components/About.vue'
import Skills from '~/components/Skills.vue'
import Experience from '~/components/Experience.vue'
import Contact from '~/components/Contact.vue'
import Footer from '~/components/Footer.vue'


export default {
  components: {
    Nav,
    About,
    Skills,
    Experience,
    Contact,
    Footer,
  }
}
</script>
<style>

body {
  background: #141213;
  color: #CFC8C2;
}

.container {
  margin: 0 auto;
  max-width: 100vw;
  height: 100vh;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 1rem;
  padding: 0 2rem 0 2rem;
}

.main-index {
  display: none;
}

img {
  display: none;
}

.title {
  grid-column: 1/5;
  font-size: 68px;
  color: #616161;
}

.section-content {
  grid-column: 1/5;
}

.section-header {
  text-transform: uppercase;
  grid-column: 2/4;
  font-size: 50px;
}

.section-index {
  color: #242424;
  font-size: 31px;
}

.section-container {
   display: grid;
   grid-template-columns: repeat(4, 1fr);
   grid-gap: 1rem;
}
</style>
