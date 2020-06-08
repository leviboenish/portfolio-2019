<template>
  <div class="section-container" id="about">
    <h3 class="sub-title">Front-End Developer</h3>
    <p class="about-content">I’m Levi Boenish, a full stack developer with a specialization in front end technologies from Denver Colorado. I’ve been writing code for the past four years and am currently working on developing user interfaces for the medical space. Outside of writing code I am an avid climber, musician, and paladin/warlock multi-class.</p>
  </div>
</template>

<script>
 export default {

    }

</script>

<style>

#about{
  grid-column: 1/5;
}

.sub-title {
  font-size: 21px;
  grid-column: 1/3;
  text-transform: uppercase;
}

@media only screen and (min-width: 1420px) {

  #about {
    margin-top: 10rem;
    grid-column: 1/13;
  }

  

  .sub-title {
    grid-column: 7/11;
  }

}
</style>