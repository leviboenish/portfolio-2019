<template>
  <div class="section-container" id="experience">
      <h1 class="section-index">02.</h1>
      <h2 class="section-header"><span class="exp-desktop">Experience</span> <span class="exp-mobile">XP</span></h2>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">Vizio</h2>
               <h3 class="dates">Nov 2022 &mdash; Present</h3>
          </div>
          <div class="job-description">
            <p>I am currently employed with Vizio as a senior software engineer. I am assisting with, and leading projects in the ad tech space to help develop internal tools for the company. I have been responsible for overhauling our front end team’s unit testing, accessibility, and styling guidelines.</p>
          </div>
      </div>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">SomaLogic</h2>
               <h3 class="dates">Jul 2019 &mdash; Nov 2022</h3>
          </div>
          <div class="job-description">
            <p>At SomaLogic I was a UX/UI engineer. I was the project owner for how our consumer facing reports are rendered. I primarily worked with HTML, CSS, and JS in Vue and we wrote our unit tests in Jest. I did everything from helping to design our apps in Figma to implementing how they were built.</p>
          </div>
      </div>
      <div class="job-history">
          <div class="job-info">
              <h2 class="company">Promontech</h2>
              <h3 class="dates">Oct 2018 &mdash; Jul 2019</h3>
          </div>
          <div class="job-description">
            <p>While working for PromonTech I primarily dealt with the logical implementation of new features in our apps. I built new features and also wrote unit tests in Jasmine. I primarily worked with HTML, CSS, and JS in AngularJS as well as Angular 6.</p>
          </div>
      </div>
  </div>
</template>

<script>
    export default {

    }
</script>

<style>
#experience {
    grid-column: 1/5;
}

.company {
    font-size: 24px;
}

.dates {
    font-size: 12px;
}

.job-history {
    grid-column: 1/5;
    margin-bottom: 2rem;
}

.job-description {
    line-height: 1.5;
}

.job-info {
    margin-bottom: 1.5rem;
}

.company, .dates {
    color: #616161;
}

.exp-desktop {
    display: none;
}

@media only screen and (min-width: 1100px) {
 
 #experience {
     grid-column: 1/13;
 }
 
 .job-history {
     grid-column: 3/10;
     display: grid;
 }

 .company, .dates {
     text-align: left;
 }

 .job-info {
     width: 9rem;
 }

 .job-description {
    grid-column: 2/6;
    margin-left: 2rem;
 }

 .exp-desktop {
     display: inline;
 }

 .exp-mobile {
     display: none;
 }
}

</style>