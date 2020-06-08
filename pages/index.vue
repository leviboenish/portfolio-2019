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

@import url('https://rsms.me/inter/inter.css');
html { font-family: 'Inter', sans-serif; }
@supports (font-variation-settings: normal) {
  html { font-family: 'Inter var', sans-serif; }
}

body {
  background: #141213;
  color: #CFC8C2;
  background-image: url('../assets/background.jpg');
  background-attachment: fixed;
  background-size: cover;
}

.container {
  margin: 0 auto;
  max-width: 35rem;
  height: 100vh;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 1rem;
  padding: 0 2rem 0 2rem;
}

.main-index {
  display: none;
  font-weight: 300;
}

img {
  display: none;
}

.title {
  grid-column: 1/5;
  font-size: 68px;
  color: #616161;
  font-weight: 200;
  text-transform: uppercase;
  line-height: .8;
  padding-bottom: 2rem;
}


.section-content, .about-content {
  grid-column: 1/5;
  line-height: 1.5;
}

.section-header {
  text-transform: uppercase;
  grid-column: 2/4;
  font-size: 50px;
  align-self: end;
  font-weight: 300;
}

.section-index {
  color: #242424;
  font-size: 31px;
  align-self: end;
  font-weight: 300;
}

.section-container {
   display: grid;
   grid-template-columns: repeat(4, 1fr);
   grid-gap: 1rem;
   margin-bottom: 5rem;
}

@media only screen and (min-width: 1100px) {
  
  .container {
    grid-template-columns: repeat(12, 1fr);
    /* padding: 5rem 10rem 0 10rem; */
    grid-gap: 3rem;
    max-width: 105rem;
  }

  img {
    display: block;
    height: 325px;
    width: auto;
    grid-column: 1/5;
  }

  .main-index {
    display: inline-block;
    color: #242424;
    font-size: 100px;
    align-self: end; 
    grid-column: 8/10;
  }

  .section-index {
    font-size: 100px;
  }

  .section-header {
      grid-column: 3/5;
      font-weight: 300;
  }

  .section-content {
    grid-column: 3/8;
  }

  .about-content{
    grid-column: 7/11;
  }

  .title {
    font-size: 132px;
    grid-column: 1/6;
    padding-bottom: 0;
  }

  .section-container {
   display: grid;
   grid-template-columns: repeat(12, 1fr);
   grid-gap: 3rem;
   margin-bottom: 5rem;
}

}
</style>
