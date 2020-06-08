<template>
  <div class="section-container" id="footer">
      <p class="footer-item" id="copy-year">Levi Boenish Portfolio&mdash;(c)2020</p>
      <p class="footer-item">Code&mdash;Levi Boenish</p>
      <p class="footer-item">Design&mdash;Henry Desroches</p>
  </div>
</template>

<script>

</script>

<style>
#footer {
    font-size: 12px;
    grid-column: 1/5;
    text-align: right;
    grid-row-gap: 0;
    margin-bottom: 1rem;
}

.footer-item {
    grid-column: 2/5;
    white-space: nowrap;
}

@media only screen and (min-width: 1420px) {
   #footer {
       grid-column: 1/13;
   }

    .footer-item {
        grid-column: 11/13;
    }

    #copy-year {
        grid-column: 1/3;
        text-align: left;
    }
}

</style>