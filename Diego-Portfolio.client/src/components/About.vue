<template>
  <!-- <div class="row">
    <div class="col-12">
      <h1 class="tag text-center">Summary</h1>

      <p class="hero-des me">
        <span
          class="typer"
          id="main"
          data-words=" a Full-Stack Software Developer, a Student, an Envisionist, an Automotive Enthusiast, "
          data-delay="100"
          data-deleteDelay="1000"
          data-loop="20"
          style="color: blue !important"
        ></span>
      </p>
    </div>
  </div> -->
  <!-- <div class="row mt-4">
    <div class="col-md-8 mx-auto text-center border-bottom">
      <p class="px-5">
        I've gone through various roads and routes to where I am now, I started
        off wanting to be a <b>mechanic</b>
        <i>"slowly found out it wasn't for me"</i>, then I studied
        <b>biology</b> for 2 years <i>"never caught my attention"</i>, and
        recently I enrolled and graduated from <b>CodeWorks</b> where I found my
        true passion for coding! Since graduating CodeWorks I've decided to go
        as a part-time student at Boise State University pursuing a Bachelors of
        Science in Computer Science while on my <b>Job Search!</b>
      </p>
    </div>
  </div> -->
  <!-- <div class="row pt-5 text-center">
    <div class="col-md-4">
      <img
        src="../assets/img/70750331-D28E-40A1-AB34-E833F92B33D4_1_105_c.jpeg"
        class="img-fluid img image-1"
        alt=""
      />
    </div>
    <div class="col-md-4">
      <img
        src="../assets/img/8DA897DC-2040-4D60-A4B5-98E1ECC2517F_1_105_c.jpeg"
        class="img-fluid img image-2"
        alt=""
      />
    </div>
    <div class="col-md-4">
      <img
        src="../assets/img/511B89E3-E0B9-4234-A310-32100BD825DD_1_105_c.jpeg"
        class="img-fluid img image-3"
        alt=""
      />
    </div>
  </div> -->

  <div class="row">
    <!-- <div class="col-md-12">
      <h2 class="tag-2 pt-5">Education</h2>
    </div> -->

    <!-- <div class="col-md-6 text-center pt-5">
      <img
        src="../assets/img/BSU-logo.png"
        class="img-fluid education-img"
        alt=""
      />
    </div> -->
    <!-- <div class="col-md-6">
      <h3 class="text-center info fonts">Boise State University</h3>
      <h4 class="text-center fonts">Bachelor of Science in Computer Science</h4>
      <h5 class="text-center fonts">2020 - 2025</h5>
    </div> -->
    <!-- <div class="col-md-6 text-center pt-5">
      <img
        src="../assets/img/Code-works.png"
        class="img-fluid education2-img"
        alt=""
      />
    </div> -->
    <!-- <div class="col-md-6">
      <h3 class="text-center info fonts">CodeWorks</h3>
      <h4 class="text-center fonts">Full-Stack Software Developer</h4>
      <h5 class="text-center mb-5 fonts">2022</h5>
    </div> -->
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
p {
  color: #444;
  letter-spacing: 1.4;
  font-family: "Poppins", sans-serif;
}

.tag {
  margin-top: 5vh;
  text-align: left;
  font-size: 4em;
  font-weight: bold;
  color: var(--hero-color);
  font-family: "CircularStd", sans-serif;
}
.tag-2 {
  margin-top: 5vh;
  text-align: left;
  font-size: 3em;
  font-weight: bold;
  color: var(--hero-color);
  font-family: "CircularStd", sans-serif;
  padding-left: 130px;
}

.me {
  padding-left: 135px;
  font-size: 1.5em;
}

@media (max-width: 780px) {
  .tag {
    text-align: center;
    padding-left: 20px;
  }
}

.img {
  height: 350px;
  width: 400px;
  /* filter: url(filters.svg#grayscale); Firefox 3.5+ */
  filter: gray; /* IE5+ */
  -webkit-filter: grayscale(1); /* Webkit Nightlies & Chrome Canary */
  -webkit-transition: all 0.8s ease-in-out;
}

.img:hover {
  filter: none;
  -webkit-filter: grayscale(0);
  -webkit-transform: scale(1.01);
}

.image-1 {
  animation: image-1 2500ms ease-in;
  animation-delay: 500ms;
}
@keyframes image-1 {
  from {
    transform: translateX(-200%);
    opacity: 0.25;
  }
  to {
    transform: translateX(0%);
    opacity: 1;
  }
}
.image-2 {
  animation: image-2 2200ms ease-in;
  animation-delay: 500ms;
}
@keyframes image-2 {
  from {
    transform: translateX(-250%);
    opacity: 0.25;
  }
  to {
    transform: translateX(0%);
    opacity: 1;
  }
}
.image-3 {
  animation: image-3 2000ms ease-in;
  animation-delay: 500ms;
}
@keyframes image-3 {
  from {
    transform: translateX(-300%);
    opacity: 0.25;
  }
  to {
    transform: translateX(0%);
    opacity: 1;
  }
}

.education-img {
  height: 350px;
  width: 400px;
}
.education2-img {
  height: 300px;
  width: 350px;
  margin-bottom: 5em;
}

.info {
  padding-top: 6em;
}

@media (max-width: 768px) {
  .info {
    padding-top: 2em;
  }

  .image-1 {
    padding-bottom: 2em;
  }
  .image-2 {
    padding-bottom: 2em;
  }

  .tag-2 {
    padding-left: 0;
    text-align: center;
  }

  .education2-img {
    margin-bottom: 0;
  }
}

.fonts {
  color: #444;
  letter-spacing: 1.4;
  font-family: "Poppins", sans-serif;
}
</style>