<template>
  <div class="section-container" id="skills">
        <h1 class="section-index">01.</h1>
        <h2 class="section-header">Skills</h2>
      <p class="section-content">I have a very specific set of skills Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fuga, voluptas perspiciatis asperiores nobis nihil qui eaque id sunt pariatur culpa provident, architecto ex dignissimos eligendi corrupti distinctio molestias cumque nam.</p>
      <ul class="skills-list-one">
          <li>Vue</li>
          <li>React</li>
          <li>Angular</li>
          <li>Node</li>
          <li>CSS</li>
          <li>HTML</li>
      </ul>
      <ul class="skills-list-two">
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

</script>

<style>

#skills {
 grid-column: 1/5;
}

.skills-list-one {
    grid-column: 1/2;
}

.skills-list-two {
    grid-column: 3/4;
}

</style>