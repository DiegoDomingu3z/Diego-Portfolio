<template>
  <nav class="nav-desk">
    <center>
      <div class="nav-logo">
        <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
          <img
            alt="logo"
            id="logo"
            class="image"
            src="../assets/img/portfolio-logo.jpeg"
          />
        </router-link>
      </div>
      <div class="nav-items">
        <ul>
          <li>
            <router-link :to="{ name: 'About' }">
              <span class="text-grey">About</span>
            </router-link>
          </li>
          <li>
            <span>
              <router-link :to="{ name: 'Projects' }"
                ><span class="text-grey">Projects</span></router-link
              >
            </span>
          </li>

          <li>
            <span>
              <router-link :to="{ name: 'Contact' }"
                ><span class="text-grey">Contact</span></router-link
              >
            </span>
          </li>
        </ul>
      </div>
    </center>
  </nav>

  <div class="menu-wrap">
    <input type="checkbox" class="toggler" />
    <div class="hamburger">
      <div></div>
    </div>
    <div class="menu">
      <div>
        <div>
          <ul>
            <li><a href="#" style="text-decoration: line-through">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="work.html">Projects</a></li>

            <li>
              <router-link :to="{ name: 'Contact' }"
                ><span class="text-dark">Contact</span></router-link
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped>
#logo {
  margin-top: 5px;
  height: 64px;
  padding: 6px;
  border: 4px solid #444;
  border-radius: 50%;
}

.nav-desk {
  height: 10vh;
  /* position: fixed; */
  display: block;
  width: 80vw;
  margin: auto;

  margin-top: 20px;
  left: 0;
  right: 0;
  /* background: black; */
}

.nav-logo {
  height: 100%;
  float: left;
}

/* .nav-items{
    color:black;
    float:right;
} */
ul {
  float: right;
  /* color:white; */
  list-style: none;
  padding: 30px 0px;
}

li {
  /* text-transform: uppercase; */
  display: inline;
  font-size: 16px;
  letter-spacing: 0.1;
  padding: 0px 15px;
}

.image {
  -webkit-animation: spin 4s linear infinite;
  -moz-animation: spin 4s linear infinite;
  animation: spin 4s linear infinite;
}
@-moz-keyframes spin {
  100% {
    -moz-transform: rotate(360deg);
  }
}
@-webkit-keyframes spin {
  100% {
    -webkit-transform: rotate(360deg);
  }
}
@keyframes spin {
  100% {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}
.menu-wrap {
  position: fixed;
  top: 50px;
  right: 50px;
  z-index: 1;
  display: none;
}

.menu-wrap .toggler {
  position: absolute;
  top: 0px;
  right: 0;
  z-index: 2;
  cursor: pointer;
  width: 50px;
  height: 50px;
  opacity: 0;
}

.menu-wrap .hamburger {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 1;
  width: 60px;
  height: 60px;
  padding: 1rem;
  background: var(--primary-color);
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Hamburger Line */
.menu-wrap .hamburger > div {
  position: relative;
  flex: none;
  width: 100%;
  height: 2px;
  z-index: 1;
  background: black;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.4s ease;
}

/* Hamburger Lines - Top & Bottom */
.menu-wrap .hamburger > div::before,
.menu-wrap .hamburger > div::after {
  content: "";
  position: absolute;
  z-index: 1;
  top: -10px;
  width: 100%;
  height: 2px;
  background: inherit;
}

/* Moves Line Down */
.menu-wrap .hamburger > div::after {
  top: 10px;
}

/* Toggler Animation */
.menu-wrap .toggler:checked + .hamburger > div {
  transform: rotate(135deg);
}

/* Turns Lines Into X */
.menu-wrap .toggler:checked + .hamburger > div:before,
.menu-wrap .toggler:checked + .hamburger > div:after {
  top: 0;
  transform: rotate(90deg);
}

/* Rotate On Hover When Checked */
.menu-wrap .toggler:checked:hover + .hamburger > div {
  transform: rotate(225deg);
}

/* Show Menu */
.menu-wrap .toggler:checked ~ .menu {
  visibility: visible;
}

.menu-wrap .toggler:checked ~ .menu > div {
  transform: scale(1);
  transition-duration: var(--menu-speed);
}

.menu-wrap .toggler:checked ~ .menu > div > div {
  opacity: 1;
  transition: opacity 0.4s ease 0.4s;
}

.menu-wrap .menu {
  position: fixed;
  top: 0;
  right: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  visibility: hidden;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.menu-wrap .menu > div {
  background: var(--overlay-color);
  border-radius: 50%;
  width: 200vw;
  height: 200vw;
  display: flex;
  flex: none;
  align-items: center;
  justify-content: center;
  transform: scale(0);
  transition: all 0.4s ease;
}

.menu-wrap .menu > div > div {
  text-align: center;
  max-width: 90vw;
  max-height: 100vh;
  opacity: 0;
  transition: opacity 0.4s ease;
}

.menu-wrap .menu > div > div > ul > li {
  list-style: none;
  color: var(--white-color);
  font-size: 1.5rem;
  padding: 1rem;
}

.menu-wrap .menu > div > div > ul > li > a {
  color: inherit;
  text-decoration: none;
  transition: color 0.4s ease;
}

.menu-wrap {
  display: block;
}

.menu ul li {
  display: block !important;
}

.menu ul li a {
  color: var(--black-color) !important;
}

.menu-wrap .hamburger {
  z-index: 2;
}

.menu-wrap .toggler {
  z-index: 3;
}

@media (max-width: 780px) {
  .nav-items {
    display: none;
  }
}
@media (min-width: 780px) {
  .menu-wrap {
    display: none;
  }
}

li:hover {
  text-decoration: line-through;
  text-decoration-color: #444;
}
</style>
