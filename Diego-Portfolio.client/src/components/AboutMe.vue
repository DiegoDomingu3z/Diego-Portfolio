<template>
  <div class="row">
    <div class="col-md-6">This working</div>
    <div class="col-md-6">
      <h1 class="about">About Me</h1>
      <div>
        <h6 class="text-muted">
          I'm glad you found your way to my page! I am a Full-Stack Developer
          from Boise, Idaho
        </h6>
      </div>
      <div class="bio-section">
        <h5>Journey</h5>
        <p>My journey has been a</p>
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
h6 {
  padding-right: 9em;
  font-size: 15px;
}
p {
  font-family: "Saira Semi Condensed", sans-serif;
  font-size: 20px;
}

.bio-section {
  margin-top: 3em;
}

@media (max-width: 768px) {
  h6 {
    padding-right: 0;
    text-align: center;
  }
  .about {
    text-align: center;
  }
}
</style>