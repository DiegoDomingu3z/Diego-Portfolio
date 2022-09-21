<template>
  <div
    class="animated fadeIn row body"
    style="width: 100vw; animation-duration: 1.5s"
  >
    <div class="col-md-6" id="left-hero">
      <h1 class="hero-tag">
        <span
          class="typer"
          id="main"
          data-words="Hey there 👋, I'm Diego!, Welcome to my page!, Feel free to contact me!, "
          data-delay="100"
          data-deleteDelay="1000"
          data-loop="20"
          style="color: blue !important"
        ></span>
        &nbsp;
      </h1>

      <p class="hero-des fs-5">
        I am a
        <b>Full-Stack Software Developer, ready to take on any challenge!</b>
      </p>

      <button class="contact-btn animated bounce delay-4s button">
        <router-link :to="{ name: 'Contact' }"
          ><span class="text-white">Contact Me</span></router-link
        >
      </button>
    </div>

    <div class="col-md-6 text-center pic" id="hero-right">
      <img class="profile rounded" src="../assets/img/diego.jpeg" />
    </div>
  </div>
</template>


<script >
import { onMounted } from '@vue/runtime-core';
import { logger } from '../utils/Logger';
export default {
  setup() {
    onMounted(async () => {
      try {
        let doc = document.createElement('script');
        doc.setAttribute('src', "https://unpkg.com/typer-dot-js@0.1.0/typer.js");
        document.head.appendChild(doc)
      } catch (error) {
        logger.log(error)
      }
    })
    return {

    }
  }
}
</script>



<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css?family=Poppins&display=swap");

@font-face {
  font-family: CircularStd;
  src: url(assets/fonts/CircularStd-Bold.eot);
  src: url("assets/fonts/CircularStd-Bold.eot?#iefix")
      format("embedded-opentype"),
    url("assets/fonts/CircularStd-Bold.woff") format("woff"),
    url("assets/fonts/CircularStd-Bold.ttf") format("truetype"),
    url("assets/fonts/CircularStd-Bold.svg#bcc26993292869431e54c666aafa8fcd")
      format("svg");
}
:root {
  --primary-color: none;
  --overlay-color: rgba(255, 255, 255, 0.9);
  --menu-speed: 0.75s;
  --light-text-color: #444;
  --black-color: #000;
  --white-color: #fff;
  --hero-color: black;
}

#left-hero {
  padding-left: 150px;
}

@media only screen and (max-width: 768px) {
  #left-hero {
    padding-left: 80px;
    flex: 0 0 100% !important;
    max-width: 100% !important;
  }

  #left-hero {
    padding-left: 50px;
  }

  .hero-tag {
    margin-top: 20vh;
    font-size: 4em;
  }

  .hero-des {
    padding-right: 30px;
  }

  #legal-hero-des {
    padding-right: 10px;
    text-align: left;
    font-size: 0.8em;
  }

  #hero-right {
    display: none;
  }
}

.hero-tag {
  margin-top: 20vh;
  text-align: left;
  font-size: 4.5em;
  font-weight: bold;
  color: var(--hero-color);
  font-family: "CircularStd", sans-serif;
}

.hero-des {
  padding-right: 60px;
  text-align: justify;
  letter-spacing: 1.4;
  font-family: "Poppins", sans-serif;
  color: #444;
}

.contact-btn {
  padding: 5px 10px;

  background: #444;
  border: 2.3px solid #444;
  transition: all 1s;
}

.contact-btn:hover {
  color: blue;
  border: 2.5px solid blue;
}

.social-icons {
  margin-top: 30%;
}

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

.profile {
  height: 40rem;
  width: 30rem;
}
.pic {
  animation: pic 2000ms ease-in;
  animation-delay: 500ms;
}
@keyframes pic {
  from {
    transform: translateX(100%);
    opacity: 0.25;
  }
  to {
    transform: translateX(0%);
    opacity: 1;
  }
}

.body {
  overflow: hidden;
}
</style>