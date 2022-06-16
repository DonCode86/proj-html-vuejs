<template>
  <div class="container">
    <section class="trainers">
      <div class="inner-container">
        <div class="section-title">
          <h2 class="text-white text-center">MEET OUR TRAINERS</h2>
        </div>
        <div class="divider text-center py-3">
          <img src="../../assets/img/divider-xx-red.png" alt="" />
        </div>
      </div>
      <div class="row justify-content-center text-white">
        <div class="col-4 card">
          <img src="../../assets/img/trainer1-200x148.jpg" alt="" />
          <div class="card-text px-4 pb-4">
            <div class="card-title my-4">
              <h3>Ann Baker</h3>
              <h3>Personal Trainer</h3>
            </div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. In auge
              nisl, onare volutpat.
            </p>
            <div class="socials d-flex">
              <div class="facebook social-icon">
                <i class="fa-brands fa-facebook-f"></i>
              </div>
              <div class="twitter social-icon">
                <i class="fa-brands fa-twitter"></i>
              </div>
              <div class="ig social-icon">
                <i class="fa-brands fa-instagram"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4 card">
          <img src="../../assets/img/trainer3-200x148.jpg" alt="" />
          <div class="card-text px-4 pb-4">
            <div class="card-title my-4">
              <h3>Anne Warren</h3>
              <h3>Personal Trainer</h3>
            </div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. In auge
              nisl, onare volutpat.
            </p>
            <div class="socials d-flex">
              <div class="facebook social-icon">
                <i class="fa-brands fa-facebook-f"></i>
              </div>
              <div class="twitter social-icon">
                <i class="fa-brands fa-twitter"></i>
              </div>
              <div class="ig social-icon">
                <i class="fa-brands fa-instagram"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4 card">
          <img src="../../assets/img/trainer4-200x148.jpg" alt="" />
          <div class="card-text px-4 pb-4">
            <div class="card-title my-4">
              <h3>Peter Rice</h3>
              <h3>Personal Trainer</h3>
            </div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. In auge
              nisl, onare volutpat.
            </p>
            <div class="socials d-flex">
              <div class="facebook social-icon">
                <i class="fa-brands fa-facebook-f"></i>
              </div>
              <div class="twitter social-icon">
                <i class="fa-brands fa-twitter"></i>
              </div>
              <div class="ig social-icon">
                <i class="fa-brands fa-instagram"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="btn-container d-flex justify-content-center p-4">
        <button>VIEW ALL TRAINERS</button>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.trainers {
  background-color: var(--secondary-color);
  padding: 6rem 0;

  h2,
  h3 {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
  }

  h3 {
    font-size: 0.9375rem;
    line-height: 0.7rem;
  }

  p {
    line-height: 1.8rem;
  }

  .col-4 {
    width: 17%;
    background-color: var(--primary-color);
    padding: 0;
    margin: 1.25rem;
  }

  .social-icon {
    background-color: var(--secondary-color);
    width: 1.875rem;
    height: 1.875rem;
    padding: 0.625rem;
    margin-right: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>
