<template>
  <header class="bg-white">
    <Navbar />
  </header>
  <main class="bg-white">
    <router-view />
  </main>
  <footer class="bg-white">
    <div class="social-icons mb-4 icons">
      <a target="_blank" href="mailto:diegodominguezf40@gmail.com"
        ><i class="fas fa-envelope"></i
      ></a>
      <a target="_blank" href="https://www.instagram.com/di3godominguez/?hl=en"
        ><i class="fab fa-instagram"></i
      ></a>
      <a target="_blank" href="https://github.com/DiegoDomingu3z"
        ><i class="fab fa-github"></i
      ></a>
      <a
        target="_blank"
        href="https://www.linkedin.com/in/diego-dominguez-b03344233"
        ><i class="fab fa-linkedin"></i
      ></a>
    </div>
  </footer>
</template>


<script>

import { computed } from 'vue';
import { AppState } from './AppState';

export default {
  name: 'App',
  setup() {
    return {
      appState: computed(() => AppState)
    }
  }
}
</script>


<style lang="scss">
@import "./assets/scss/main.scss";

.social-icons a:hover {
  color: blue;
}

.social-icons a {
  color: #444;
  text-decoration: none;
  transition: all 1s;
}

.social-icons i {
  font-size: 2em;
  /* font-weight: 100; */
  padding: 0px 5px;
}

.social-icons {
  padding-left: 135px;
}

@media (max-width: 780px) {
  .social-icons {
    padding-left: 120px;
  }
}
</style>
