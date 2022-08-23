<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import Personal from './components/Personal.vue'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/jipa.jpg" style="max-width: 30%; border: none; outline: none; height: 250px;" />
    <HelloWorld/>
    <div class="wrapper">
      <personal msg="My Name is Zivani Aidin" />

      <nav>
        <RouterLink to="/">Personal</RouterLink>
        <RouterLink to="/skill">Skill</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />

  <footer>
    <div class="footer-isi">
      <div class="logo-1">
      <div class="kiri">
        <img src="../src/assets/telephone.svg" alt="">
      </div>
      <div class="kanan">
        <a href="">+62 812-8190-4726</a>
      </div>
    </div>
     <div class="logo-1">
      <div class="kiri">
        <img src="../src/assets/envelope.svg" alt="">
      </div>
      <div class="kanan">
      <a href="">zivania04@gmail.com</a>
      </div>
    </div>
     <div class="logo-1">
      <div class="kiri">
        <img src="../src/assets/github.svg" alt="">
      </div>
      <div class="kanan">
        <a href="">github.com/zivania02</a>
      </div>
    </div>
    </div>
    
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  margin-bottom: 3rem;
  background-color: #D7A86E;
  width: 1000px;
  padding: 20px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 20px;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }

  
  footer{
    background-color: #D8CCA3;
    height: 150px;
  }
  .logo-1{
    display: flex;
    gap: 1rem;
  }

  .logo-1 a{
    color: black;
  }

  .logo-1 p{
    color: black;
  }

  .footer-isi{
    margin-left: 70px;
    padding-top: 40px;
  }
}

</style>
