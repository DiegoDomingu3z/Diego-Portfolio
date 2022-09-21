<template>
  <div>
    <div
      class="fadeIn row"
      style="width: 100vw; height: auto; animation-duration: 1.5s"
    >
      <div class="col-md-12" id="left-hero">
        <h1 class="hero-tag contact-hero fadeInLeft">My Projects!</h1>
        <p class="info contact-des fadeIn delay-1s">
          Take a look at some of my Full-stack & front-end applications I've
          developed!
        </p>
      </div>
    </div>
    <div class="animated bounceInUp delay-1s">
      <div class="row pt-5">
        <div class="col-md-6 col-sm-12 bounceInLeft delay-2s">
          <center>
            <div
              id="keepR"
              class="carousel slide carousel-fade"
              data-bs-ride="carousel"
            >
              <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/Keepr-home.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/Keepr-create.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/Keepr-Modal.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="../assets/img/Keepr-profile.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#keepR"
                data-bs-slide="prev"
              >
                <span
                  class="mdi mdi-arrow-left-drop-circle carousel-left-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#keepR"
                data-bs-slide="next"
              >
                <span
                  class="mdi mdi-arrow-right-drop-circle carousel-right-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </center>
        </div>
        <div class="col-md-6 col-sm-12">
          <div class="work-des">
            <h1>Keepr</h1>
            <center></center>
            <p class="info">
              Keepr was designed for users to have a platform to share their
              keeps "pictures" across the applications with other users. The
              application allows users to create albums "vaults" and insert all
              the keeps they wish to desire. Keepr allows for all users to have
              public profiles and have all their keeps and vaults shared to the
              public, but also gives the option to make vaults private and
              hidden from other users. A search bar was implemented to give
              users an easier and faster way of finding a Keep based on their
              name.
            </p>
            <div class="technologies">
              <h2>Technologies Used</h2>
              <span class="tech-stack"> CSharp </span>
              <span class="tech-stack"> JavaScript </span>
              <span class="tech-stack"> .Net Framework </span>
              <span class="tech-stack"> Vue.js </span>
              <span class="tech-stack"> MySQL </span>
              <span class="tech-stack"> HTML </span>
              <span class="tech-stack"> CSS </span>
              <span class="tech-stack"> Bootstrap </span>
            </div>
            <div class="d-flex justify-content-between mt-4">
              <a href="https://github.com/DiegoDomingu3z/Keepr">
                <i
                  title="Source Code"
                  class="fs-2 fab fa-github source-code"
                ></i>
              </a>
              <span class="pt">
                <a href="https://diego-keepr.herokuapp.com">
                  <button class="contact-btn work-read">Go to website</button>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="row pt-5">
        <div class="col-md-6 col-sm-12 bounceInLeft delay-2s">
          <center>
            <div
              id="OnTracker-carousel"
              class="carousel slide carousel-fade"
              data-bs-ride="carousel"
            >
              <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/OnTracker-home.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/OnTracker-bus.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/OnTracker-Project.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="../assets/img/OnTracker-create.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#OnTracker-carousel"
                data-bs-slide="prev"
              >
                <span
                  class="mdi mdi-arrow-left-drop-circle carousel-left-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>

              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#OnTracker-carousel"
                data-bs-slide="next"
              >
                <span
                  class="mdi mdi-arrow-right-drop-circle carousel-right-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </center>
        </div>
        <div class="col-md-6 col-sm-12">
          <div class="work-des">
            <h1>OnTracker</h1>

            <p class="info">
              On-Tracker was built with a group of 4 developers, designed to
              make tracking projects and progress around town easier. On-Tracker
              gives the user an option to create a business or become any
              employee of a business. The creator of a business can create
              projects that they may have locally or globally. This was made
              possible by using the MapBox Api to drop pins on a fully
              functional map. Images, Tasks, and notes can be added to a
              projects. On-tracker allows business owners to assign specific
              employees to a projects and gives the employees access to mark
              tasks as complete.
            </p>
            <div class="technologies">
              <h2>Technologies Used</h2>
              <span class="tech-stack"> JavaScript</span>
              <span class="tech-stack"> Node.js</span>
              <span class="tech-stack"> Vue.js</span>
              <span class="tech-stack"> HTML</span>
              <span class="tech-stack"> CSS</span>
              <span class="tech-stack"> Bootstrap </span>
              <span class="tech-stack"> MongoDb</span>
            </div>
            <div class="d-flex justify-content-between mt-5">
              <a href="https://github.com/DiegoDomingu3z/on-tracker">
                <i
                  title="Source Code"
                  class="fs-2 fab fa-github source-code"
                ></i>
              </a>
              <span class="pt">
                <a href="https://ontracker-capstone.herokuapp.com">
                  <button class="contact-btn work-read">Go to website</button>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="row pt-5">
        <div class="col-md-6 col-sm-12 bounceInLeft delay-2s">
          <center>
            <div
              id="allSpice"
              class="carousel slide carousel-fade"
              data-bs-ride="carousel"
            >
              <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/All-Spice-home.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/All-spice-info.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
                <div class="carousel-item active" data-bs-interval="3000">
                  <img
                    src="../assets/img/All-spice-create.png"
                    class="d-block img user-picture"
                    alt="..."
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#allSpice"
                data-bs-slide="prev"
              >
                <span
                  class="mdi mdi-arrow-left-drop-circle carousel-left-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#allSpice"
                data-bs-slide="next"
              >
                <span
                  class="mdi mdi-arrow-right-drop-circle carousel-right-button"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </center>
        </div>
        <div class="col-md-6 col-sm-12">
          <div class="work-des">
            <h1>All-Spice</h1>

            <p class="info">
              All Spice is an application developed to allow users to create
              recipes and add ingredients and steps to allow other users to
              closely follow the recipe plan. Once logged in users are allowed
              to add their own recipes for other users to see. All Spices allows
              users to favorite recipes and create a collection of all recipes
              they have favorited. MySQL was used as the database for this
              application and the backend being built with C#. The front end was
              created and designed using JavaScript Vue.js, HTML, CSS and
              Bootstrap.
            </p>
            <div class="technologies">
              <h2>Technologies Used</h2>
              <span class="tech-stack"> CSharp </span>
              <span class="tech-stack"> JavaScript </span>
              <span class="tech-stack"> .Net Framework </span>
              <span class="tech-stack"> Vue.js </span>
              <span class="tech-stack"> MySQL </span>
              <span class="tech-stack"> HTML </span>
              <span class="tech-stack"> CSS </span>
              <span class="tech-stack"> Bootstrap </span>
            </div>
            <div class="d-flex justify-content-between mt-5">
              <a href="https://github.com/DiegoDomingu3z/All_Spice">
                <i
                  title="Source Code"
                  class="fs-2 fab fa-github source-code"
                ></i>
              </a>
              <span class="pt">
                <a href="https://diego-all-spice.herokuapp.com">
                  <button class="contact-btn work-read">Go to website</button>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="row pt-5">
        <div class="col-md-6 col-sm-12 bounceInLeft delay-2s">
          <center>
            <div class="work-hero mb-5">
              <img class="img-fluid img" src="../assets/img/event-search.png" />
            </div>
          </center>
        </div>
        <div class="col-md-6 col-sm-12 pb-5">
          <div class="work-des">
            <h1>Tower</h1>

            <p class="info">
              Tower is an application that was developed to allows user to find
              events going on around town. This applications gives logged in
              users the ability to get a ticket for specific events, which
              brings the count down of available tickets for that events. If
              events are out of tickets, the event is marked as sold out,
              disabling the ability to get a ticket for that event. Tower also
              gives users the ability to connect through comments with others
              users attending the same event. Tower provides easier access to
              find events by category by the implementation of a filter at the
              top of the home page.
            </p>
            <div class="technologies">
              <h2>Technologies Used</h2>
              <span class="tech-stack"> JavaScript</span>
              <span class="tech-stack"> Node.js</span>
              <span class="tech-stack"> Vue.js</span>
              <span class="tech-stack"> HTML</span>
              <span class="tech-stack"> CSS</span>
              <span class="tech-stack"> Bootstrap </span>
              <span class="tech-stack"> MongoDb</span>
            </div>

            <div class="d-flex justify-content-between mt-5">
              <a href="https://github.com/DiegoDomingu3z/Tower">
                <i
                  title="Source Code"
                  class="fs-2 fab fa-github source-code"
                ></i>
              </a>
              <span class="pt">
                <a href="https://tower-finder.herokuapp.com">
                  <button class="contact-btn work-read">Go to website</button>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
import { onMounted } from '@vue/runtime-core'
export default {
  setup() {

    return {



    }
  }
}
</script>


<style lang="scss" scoped>
:root {
  --primary-color: none;
  --overlay-color: rgba(255, 255, 255, 0.9);
  --menu-speed: 0.75s;
  --light-text-color: #444;
  --black-color: #000;
  --white-color: #fff;
  --hero-color: black;
}

.carousel-right-button {
  color: rgb(210, 210, 210) !important;
  font-size: 50px;
  padding-left: 1.2em;
}
.carousel-left-button {
  color: rgb(210, 210, 210) !important;
  font-size: 50px;
  padding-left: 0.8em;
}

i {
  /* font-weight: 100; */
  padding: 5px 10px;
}
.img {
  width: 100%;
  padding-left: 50px;
}

#left-hero {
  padding-left: 150px;
}

.image {
  -webkit-animation: spin 4s linear infinite;
  -moz-animation: spin 4s linear infinite;
  animation: spin 4s linear infinite;
}
.work-read {
  float: none;
}

@media only screen and (max-width: 768px) {
  .hero-tag {
    margin-top: 10vh;
    font-size: 4em;
  }

  .carousel-left-button {
    padding-left: 0;
    font-size: 20px;
  }
  .carousel-right-button {
    padding-left: 0;
    font-size: 20px;
  }

  .project-star {
    display: none;
  }

  .project-star-mobile {
    display: block;
  }
}
.hero-tag {
  text-align: left;
  font-size: 3.5em;
  font-weight: bold;
  color: black;
  font-family: "CircularStd", sans-serif;
}

.work-hero-card {
  display: block;
  margin: 0 auto;
  width: 80%;
  background: #fff;
  align-items: center;
  padding: 0;
  /* border-radius: 10px; */
  padding-bottom: 15px;
  /* border:1px solid #44444450; */
  box-shadow: 1px 1px 20px #00000025;
  cursor: pointer;
  transition: all 1s;
  height: 100%;
}

.work-hero-card:hover {
  width: 85%;
  box-shadow: 0px 0px 20px #88888875;
  animation: zoom 1s;
  /* filter: none; */
}

.work-hero {
  /* border:2px solid #444; */
  border-radius: 10px;
  /* box-shadow: 0px 0px 5px #444; */
  width: 90%;
  transition: width 1s;
}

.work-hero:hover {
  width: 95%;
}

.work-hero-img {
  width: 100%;
  border-radius: 10px;
}

@media (min-width: 768px) and (max-width: 1024px) {
  .work-hero {
    width: 100%;
  }
}

@media (max-width: 768px) {
  .work-hero-card {
    width: 100%;
    margin-bottom: 25px;
  }

  .info {
    padding-right: 0em !important;
  }

  .img {
    padding-left: 0px !important;
  }

  #left-hero {
    padding-left: 0px;
    text-align: center;
  }

  .hero-tag {
    text-align: center;
  }

  .source-code {
    display: none;
  }
}

.work-des h1 {
  font-weight: bold;
  color: #444;
}
.work-des p {
  text-align: justify;
  font-weight: 100;
}

.technologies h2 {
  font-size: 0.8em;
  font-weight: bold;
}

.tech-stack {
  cursor: pointer;
  margin-right: 10px;
  background: #f2f2f2;
  padding: 2px 4px;
  font-size: 0.8em;
  transition: background 1s;
}

.tech-stack:hover {
  background: beige;
}

.contact-btn {
  padding: 5px 10px;
  color: #444;
  background: none;
  border: 2px solid #444;
  transition: all 1s;
}

.contact-btn:hover {
  color: white;
  background-color: #444;
  border: 2px solid #444;
}

.info {
  padding-right: 8em;
  font-family: "Poppins", sans-serif;
  color: rgb(74, 74, 74);
  letter-spacing: 1.4;
}

.pt {
  padding-right: 125px;
}
</style>