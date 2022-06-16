<template>
  <div class="container">
    <section class="section-workout">
      <div class="inner-container">
        <div class="row">
          <div class="col-3">
            <div class="card-container">
              <div class="logo">
                <i class="fa-solid fa-link-slash"></i>
              </div>
              <h3 class="text-white">Strength & Conditioning</h3>
              <div class="divider text-center py-2">
                <img src="../../assets/img/divider-x-red.png" alt="" />
              </div>
              <p class="text-center">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. In
                augue nisi, ornare es volutpat etra us.
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="logo">
              <i class="fa-solid fa-bicycle"></i>
            </div>
            <h3 class="text-white">Fitness & Cardio</h3>
            <div class="divider text-center py-2">
              <img src="../../assets/img/divider-x-red.png" alt="" />
            </div>
            <p class="text-center">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. In augue
              nisi, ornare es volutpat etra us.
            </p>
          </div>
          <div class="col-3">
            <div class="logo">
              <i class="fa-brands fa-skyatlas"></i>
            </div>
            <h3 class="text-white">Flexibility & Rest</h3>
            <div class="divider text-center py-2">
              <img src="../../assets/img/divider-x-red.png" alt="" />
            </div>
            <p class="text-center">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. In augue
              nisi, ornare es volutpat etra us.
            </p>
          </div>
          <div class="col-3">
            <div class="logo">
              <i class="fa-solid fa-heart-pulse"></i>
            </div>
            <h3 class="text-white">Health & Diet</h3>
            <div class="divider text-center py-2">
              <img src="../../assets/img/divider-x-red.png" alt="" />
            </div>
            <p class="text-center">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. In augue
              nisi, ornare es volutpat etra us.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.section-workout {
  background-image: url(../../assets/img/gym_bkgd_bw-compressor.jpg);
  background-position: center;
  padding: 5.5rem 0;

  .logo {
    color: #ff0000;
    font-size: 2rem;
    width: 5rem;
    height: 5rem;
    border: 1px solid #ff0000;
    border-radius: 100%;
    text-align: center;
    line-height: 5rem;
    margin: 0.8rem auto;
  }

  h3 {
    font-size: 1rem;
    font-family: "Montserrat", sans-serif;
    font-weight: 600;
    text-align: center;
  }

  p {
    font-size: 0.75rem;
    line-height: 1.6rem;
  }
}
</style>
