<template>
  <div class="section-container" id="experience">
      <h1 class="section-index">02.</h1>
      <h2 class="section-header"><span class="exp-desktop">Experience</span> <span class="exp-mobile">XP</span></h2>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">SomaLogic</h2>
               <h3 class="dates">July 2019 &mdash; Present</h3>
          </div>
          <p>While working for PromonTech I primarily dealt with the logical implementation of new features in our apps. I built new features and also wrote unit tests in Jasmine. I primarily worked with HTML, CSS, and JS in AngularJS as well as Angular 6.</p>
      </div>
      <div class="job-history">
          <div class="job-info">
              <h2 class="company">Promontech</h2>
              <h3 class="dates">October 2018 &mdash; July 2019</h3>
          </div>
          <p>At SomaLogic I am currently a UX/UI engineer. I am the project owner for how our consumer facing reports are rendered. I primarily work with HTML, CSS, and JS in Vue and we write our unit tests in Jest. I do everything from helping to design our apps in Figma to implementing how they are built.</p>
      </div>

  </div>
</template>

<script>

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
     display: flex;
 }

 .company, .dates {
     text-align: right;
 }


 .job-info {
    margin-right: 1rem;
    width: 25rem;
 }

 .exp-desktop {
     display: inline;
 }

 .exp-mobile {
     display: none;
 }
}

</style>