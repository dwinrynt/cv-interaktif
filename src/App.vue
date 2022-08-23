<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Personal from './components/Personal.vue'
import Footer from './components/Footer.vue' 
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink class="link-p" to="/">Personal</RouterLink>
        <RouterLink class="link-s" to="/skill">Skill</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
  <Footer />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.link-p{
  margin-left: 25px;
}

/* .link-s{
  margin-left: 10px;
} */

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
    text-align: center;
    font-size: 1rem;
    padding-left: 2rem;
    padding-top: 2rem;
    margin-bottom: -50px;
  }

  
}
</style>
