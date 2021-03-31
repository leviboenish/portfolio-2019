<template>
  <div class="section-container" id="experience">
      <h1 class="section-index">02.</h1>
      <h2 class="section-header"><span class="exp-desktop">Experience</span> <span class="exp-mobile">XP</span></h2>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">A2Z Sync</h2>
               <h3 class="dates">Jul 2021 &mdash; Present</h3>
          </div>
          <div class="job-description">
            <p>I am currently a Full Stack Engineer at A2Z sync. I am specializing in react to help build a new app to propel the way we buy cars into the future. Within this app I am writing everything from styles to business logic. We are also using Cypress and PHP to test and develop back end code for our apps.</p>
          </div>
      </div>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">SomaLogic</h2>
               <h3 class="dates">Jul 2019 &mdash; Jan 2021</h3>
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
}

.company, .dates {
    color: #616161;
}

.exp-desktop {
    display: none;
}

@media only screen and (min-width: 600px) {
 
 #experience {
     grid-column: 1/13;
 }
 
 .job-history {
     grid-column: 2/10;
     display: grid;
     grid-template-columns: repeat(6, 1fr);
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