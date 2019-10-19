<template>
  <div class="container">
    <Nav />
    <img src="../assets/me.jpg" alt="">
    <h1 class="title">
      Levi Boenish
    </h1>
    <h1 class="about-index">00</h1>
    <About />
    <Skills />
    <Experience />
    <Contact />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import About from '~/components/About.vue'
import Skills from '~/components/Skills.vue'
import Experience from '~/components/Experience.vue'
import Contact from '~/components/Contact.vue'


export default {
  components: {
    Nav,
    About,
    Skills,
    Experience,
    Contact
  }
}
</script>
<style>

.container {
  margin: 0 auto;
  max-width: 60rem;
  min-height: 100vh;
  border: 1px solid red;
  display: grid;
  grid-template-columns: repeat(12, 1fr);
}

img {
  width: 15rem;
  height: auto;
}

Nav {
  grid-column: 11/13;
}

.title {
  grid-column: 1/8;
}

.about-index{
  grid-column: 9/11
}

</style>
