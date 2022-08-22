<template>
  <div
    class="animated fadeIn row"
    style="width: 100vw; animation-duration: 1.5s"
  >
    <div class="col-md-6" id="left-hero">
      <h1 class="hero-tag contact-hero animated fadeInLeft">
        Let's Get In Touch.
      </h1>

      <div class="form-group animated fadeInLeft">
        <div class="heads">
          <label for="name"
            >Email
            <a target="_blank" href="mailto:diegodominguezf40@gmail.com"
              ><i
                class="fas fa-envelope animated bounce delay-4s button"
              ></i></a
          ></label>
        </div>
        <p class="fs-4 pt-3 p">diegodominguezf40@gmail.com</p>
      </div>
      <div class="form-group animated fadeInLeft">
        <div class="heads">
          <label for="email">Phone</label>
        </div>
        <p class="fs-4 pt-3 p">(208)-803-7936</p>
      </div>
      <div class="form-group animated fadeInLeft">
        <div class="heads">
          <label for="email">Linkedin</label>
        </div>
        <a href="https://www.linkedin.com/in/diego-dominguez-b03344233/">
          <p class="fs-4 pt-3">Diego-Dominguez</p>
        </a>
        <a
          href="https://www.linkedin.com/in/diego-domingu3z/overlay/1635499132699/single-media-viewer/"
        >
          <button class="download-btn text-white">Download Resume</button>
        </a>
      </div>

      <br />
    </div>

    <div class="col-md-6" id="hero-right">
      <img
        class="animated fadeInRight"
        id="hero-img"
        src="../assets/img/contact.svg"
      />
    </div>
  </div>
</template>


<script>
export default {
  setup() {
    return {}
  }
}
</script>


<style lang="scss" scoped>
.download-btn {
  padding: 5px 10px;

  background: #444;
  border: 2.3px solid #444;
  transition: all 1s;
}
#left-hero {
  padding-left: 150px;
}
.hero-tag {
  text-align: left;
  font-size: 3.5em;
  font-weight: bold;

  font-family: "CircularStd", sans-serif;
}

#hero-img {
  margin-top: 45px;
  width: 90%;
}

.work-card-hero-img {
  width: 100%;
  display: block;
  /* border:1px solid #44444450; */
  /* border-radius: 10px; */
  border-bottom: none;
  margin: 0 auto;
  left: 0;
  right: 0;
}

@media only screen and (max-width: 768px) {
  #hero-right {
    display: none;
  }

  #left-hero {
    padding-left: 0;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  #hero-right {
    display: none;
  }

  #left-hero {
    padding-left: 0;
  }
}

.heads {
  font-size: 30px;
  border-bottom: 2px solid #444;
  letter-spacing: 1.4;
  font-family: "Poppins", sans-serif;
}

.p {
  color: #444;
  letter-spacing: 1.4;
  font-family: "Poppins", sans-serif;
}

i {
  color: #444;
}
</style>