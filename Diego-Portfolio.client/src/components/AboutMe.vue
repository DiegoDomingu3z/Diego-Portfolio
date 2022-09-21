<template>
  <div class="row about-section">
    <div class="col-md-6 text-center">
      <img
        class="img-fluid pic rounded"
        src="../assets/img/E8671E67-FD29-460F-BFCB-C9B296DC2146_1_105_c.jpeg"
        alt=""
      />
    </div>
    <div class="col-md-6">
      <h1 class="header">About Me</h1>
      <div>
        <p>
          Hello! My name Diego Dominguez, I am a proud Mexican-American/Chicano,
          I was born in a small town in Idaho called Mountain Home. Growing up I
          was always fascinated by technology and cars, any chance I got I
          always found myself taking apart an old phone or a part off of my dads
          old junk cars and trying to put it back together. I wasn't always
          <b>100%</b> successful putting them back together, but I always found
          so much satisfaction whenever I was able to, especially doing it by
          myself. Fast forward to today I have found that same satisfaction I
          got as a kid but now building out full-stack applications, being able
          to carry out that same passion today is what keeps me motivated to
          learn more everyday.
        </p>
        <p>
          For the past 2 years I had been a full time student at Boise State
          University, but have recently started taking only a few
          <b>online</b> classes as I continue my job search. I still plan on
          getting my Bachelors of Science within the next few years, but have
          recently put my focus on breaking into tech industry as I feel I have
          the necessary skills!
        </p>
      </div>
    </div>
  </div>
  <div class="row bio-section mt-5">
    <div class="col-md-6">
      <h1 class="header">Journey</h1>
      <div>
        <p>
          I started attending <b>Boise State University</b> in 2020, I
          originally started off as <b>Biology Major</b>, growing up with a
          family with almost everyone in medicine I had felt an obligation to
          continue the trend. After a couple semesters of feeling unhappy and
          unmotivated with where I was taking my next chapters in life I finally
          decided enough was enough and started exploring different fields to
          study.
        </p>

        <p>
          During this time, I was taking up a hobby of sim racing, I started out
          building a simulator rig, most of the parts were bolt ons but me
          wanting to go above and beyond I started building a wind simulator to
          blast air into my face depending on the speed I was going, this is
          where coding first came into play in my life. Minimal coding was
          involved to hook up the software to an arduino I had wired to my pc
          and fans, but it blew my mind seeing my lines of code and the software
          lines of code spill all over my screen and go to work. I was instantly
          intrigued and new I had to read more about these little lines of code
          I had never seen before.
        </p>
        <p>
          Fast forward a couple months I decided to change my major to Computer
          Science and had also decided to attend
          <b>Boise CodeWorks</b> as a Full Stack Developer student. Since
          deciding to make my own career choices there hasn't been a day where I
          have felt unmotivated to learn more and more.
        </p>
      </div>
    </div>
    <div class="col-md-6 text-center">
      <img class="img-fluid car" src="../assets/img/loading-img.webp" alt="" />
    </div>
  </div>
  <div class="row education-section">
    <h1 class="header">Education</h1>
    <div class="col-md-6">
      <div class="card">
        <div class="card__side card__side--front-1 rounded">
          <div class="card__title card__title--1 text-center">
            <img
              class="img-fluid bsu"
              src="../assets/img/BSU-logo.png"
              alt=""
            />
          </div>
        </div>
        <div class="card__side card__side--back">
          <div class="text-center mt-5">
            <p class="text">Boise State University</p>
            <p class="text-2">Bachelors of Science in Computer Science</p>
            <p class="text-3">2020-2025</p>
          </div>
        </div>
      </div>
    </div>
    <div class="col-md-6">
      <div class="card">
        <div class="card__side card__side--front-1">
          <div class="card__title card__title--1 text-center">
            <img
              class="img-fluid code-works"
              src="../assets/img/Code-works.png"
              alt=""
            />
          </div>
        </div>
        <div class="card__side card__side--back">
          <div class="text-center mt-5">
            <p class="text">CodeWorks</p>
            <p class="text-2">Full-Stack Software Developer Certificate</p>
            <p class="text-3">2022</p>
          </div>
        </div>
      </div>
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
.card {
  -webkit-perspective: 150rem;
  perspective: 150rem;
  -moz-perspective: 150rem;
  position: relative;
  height: 25rem;
  margin-top: 3em;
  margin-bottom: 3em;
  cursor: pointer;
}

.card__side {
  height: 25rem;
  -webkit-transition: all 0.8s ease;
  transition: all 1.5s ease;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  border-radius: 3px;
  overflow: hidden;
  -webkit-box-shadow: 0 1.5rem 4rem rgba(0, 0, 0, 0.15);
  box-shadow: 0 1.5rem 4rem rgba(0, 0, 0, 0.15);
}

.text {
  font-family: "Saira Condensed", sans-serif;
  font-size: 50px;
}
.text-2 {
  font-family: "Saira Condensed", sans-serif;
  font-size: 30px;
}
.text-3 {
  font-family: "Saira Condensed", sans-serif;
  font-size: 25px;
}

.header {
  font-family: "CircularStd", sans-serif;
  font-weight: bold;
}

.card__side--back {
  -webkit-transform: rotateY(180deg);
  transform: rotateY(180deg);
}

.card:hover .card__side--front-1 {
  -webkit-transform: rotateY(-180deg);
  transform: rotateY(-180deg);
}

.card:hover .card__side--back {
  -webkit-transform: rotateY(0);
  transform: rotateY(0);
}

h6 {
  padding-right: 9em;
  font-size: 15px;
}
p {
  font-family: "Saira Semi Condensed", sans-serif;
  font-size: 20px;
}

.bio-section {
  margin-bottom: 5em;
  height: 90vh;
}

.about-section {
  height: 80vh;
  margin-top: 3em;
}

.education-section {
  height: 85vh;
  margin-top: 3em;
}

.pic {
  height: 65%;
}

.bsu {
  width: 50%;
  margin-top: 1.5em;
}

.code-works {
  width: 45%;
  margin-top: 3em;
}

.car {
  transform: rotate(120deg);
  width: 100%;
  margin-top: 13em;
}

@media (max-width: 768px) {
  h6 {
    padding-right: 0;
    text-align: center;
  }

  .bio-section {
    margin-bottom: 0;
    height: auto;
  }

  .about-section {
    height: auto;
    margin-top: 3em;
  }

  .car {
    display: none;
  }

  .pic {
    padding-top: 1em;
    padding-bottom: 2em;
    height: 85%;
  }
}
</style>