<template>
  <div class="container">
    <section class="join-us">
      <div class="inner-container d-flex">
        <div class="text-container">
          <h2>Achieve Your Fitness Goals</h2>
          <h4>
            Flexible membership packages to suit all levels of athlete and
            achive your fitness goals
          </h4>
        </div>
        <div class="btn-container align-self-center">
          <button>JOIN US</button>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.join-us {
  background-image: url("../../assets/img/home-parallax.jpg");
  background-size: cover;
  background-position-y: -114px;

  .text-container {
    padding: 3.125rem 0;
  }
  h2 {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
    color: #fff;
    font-size: 1.8rem;
  }

  h4 {
    font-size: 0.8rem;
    color: #fff;
  }

  button {
    font-size: 1.2rem;
    margin-left: 10rem;
  }
}
</style>
