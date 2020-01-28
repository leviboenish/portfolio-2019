<template>
  <div class="section-container" id="experience">
      <h1 class="section-index">02.</h1>
      <h2 class="section-header">Exp erience</h2>
      <div class="job-history">
          <div class="job-info">
               <h2 class="company">SomaLogic</h2>
               <h3 class="dates">July 2019 &mdash; Present</h3>
          </div>
          <p>Blurb about Soma Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea esse dolorem distinctio voluptas quae impedit vero nihil eius.</p>
      </div>
      <div class="job-history">
          <div class="job-info">
              <h2 class="company">Promontech</h2>
              <h3 class="dates">October 2018 &mdash; July 2019</h3>
          </div>
          <p>Blurb about Ptech Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea esse dolorem distinctio voluptas quae impedit vero nihil eius.</p>
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
}

</style>