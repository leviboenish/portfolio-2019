<template>
  <nav>
      <ul>
          <li class="nav-item"><a class="nav-link" href="#about">00 ABOUT</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">01 SKILLS</a></li>
          <li class="nav-item"><a class="nav-link" href="#experience">02 EXP</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">03 CONTACT</a></li>
      </ul>
  </nav>
</template>

<script>

</script>

<style>

a {
  text-decoration: none;
  color: #CFC8C2;
}

.nav-link:active, .nav-link:hover {
  color: #242424;
}

nav {
  grid-column: 1/3;
  padding-top: 5rem;
}

ul {
    list-style-type: none;
    padding: 0;
}

@media only screen and (min-width: 1420px) {
  
  nav{
    grid-column: 11/13;
  }

 .nav-item {
   padding: 3px;
 }

}

</style>