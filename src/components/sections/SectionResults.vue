<template>
  <div class="container">
    <section class="results">
      <div class="inner-container">
        <div class="section-title">
          <h2 class="text-white text-center">REAL WORLD RESULTS</h2>
        </div>
        <div class="divider text-center py-3">
          <img src="../../assets/img/divider-xx-red.png" alt="" />
        </div>
        <div class="row text-white">
          <div class="col-6">
            <img src="../../assets/img/review_1-compressor.jpg" alt="" />
            <div class="text-card">
              <p class="people-text">
                "The trainers at Avada Gym have helped me reach my fitness goals
                beyond anything i could of hoped for. I love it!"
              </p>
              <p class="people-name">- Tara Smith</p>
            </div>
          </div>
          <div class="col-6">
            <img src="../../assets/img/review_3-compressor-2.jpg" alt="" />
            <div class="text-card">
              <p class="people-text">
                "The atmosphere at Avada Gym is amazing, the people are even
                better. All in all, it is a great place to work out."
              </p>
              <p class="people-name">- Simon Chel</p>
            </div>
          </div>
          <div class="col-6">
            <img src="../../assets/img/review_2-compressor.jpg" alt="" />
            <div class="text-card">
              <p class="people-text">
                "The facilities at Avada Gym stood out to me the most. They are
                well maintained and have high quality equipment."
              </p>
              <p class="people-name">- Jen Wirth</p>
            </div>
          </div>
          <div class="col-6">
            <img src="../../assets/img/review_4-compressor-2.jpg" alt="" />
            <div class="text-card">
              <p class="people-text">
                "No bad things to say about Avada Gym, they are top notch at
                every corner and truly take care of their costumers."
              </p>
              <p class="people-name">- Jeff Glum</p>
            </div>
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
.results {
  background-color: var(--primary-color);
  padding: 6rem 0;

  .col-6 img {
    width: 7rem;
    height: 7rem;
    margin-right: 1rem;
  }
  h2 {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
  }

  .col-6 {
    background-color: var(--secondary-color);
    width: 45%;
    margin: 1.25rem;
    padding: 1.25rem;
    display: flex;
  }

  .people-text {
    font-size: 0.7rem;
    font-style: italic;
    line-height: 1.4rem;
    margin-bottom: 0.3rem;
  }

  .people-name {
    font-weight: 700;
    font-size: 0.775rem;
  }
}
</style>
