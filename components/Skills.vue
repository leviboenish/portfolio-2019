<template>
  <div class="section-container" id="skills">
        <h1 class="section-index">01.</h1>
        <h2 class="section-header">Skills</h2>
      <p class="section-content">I started out by teaching myself how to code using Codecademy and Treehouse. When I discovered and aptitude and passion for writing code, I decided to attend Front Range Community College to pursue a certificate in front end technologies. Upon finishing the program, I decided I hadn’t had enough so I attended Galvanize, a 6-month immersive full stack development course. Four months into the program I started working professionally as a front-end engineer.</p>
      <ul class="skills-list">
          <li>Vue</li>
          <li>React</li>
          <li>Angular</li>
          <li>Node</li>
          <li>CSS</li>
          <li>HTML</li>
          <li>Java</li>
          <li>SQL</li>
          <li>Gatsby</li>
          <li>Nuxt</li>
          <li>ES6</li>
          <li>SCSS</li>
      </ul>
  </div>
</template>

<script>
 export default {

    }

</script>

<style>

#skills {
 grid-column: 1/5;
}

.skills-list {
    grid-column: 1/5; 
    column-count: 2;
    column-gap: 12rem;
}

@media only screen and (min-width: 1100px) {
    #skills {
        grid-column: 1/12;
    }

    .skills-list {
        grid-column: 9/11;
        column-gap: 4rem;
    }
}

</style>