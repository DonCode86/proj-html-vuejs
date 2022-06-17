<template>
  <div class="container">
    <section class="news">
      <div class="inner-container">
        <div class="section-title">
          <h2 class="text-white text-center">PERFORMANCE NEWS</h2>
        </div>
        <div class="divider text-center py-3">
          <img src="../../assets/img/divider-xx-red.png" alt="" />
        </div>
        <div class="cards-container">
          <div class="card">
            <img src="../../assets/img/blog1-200x104.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>Train with free weights or your body weight?</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
          <div class="card card-2">
            <img src="../../assets/img/blog6.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>Nutritional advice that will keep you training</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
          <div class="card card-3">
            <img src="../../assets/img/trainer4.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>Nutritional advice that will keep you training</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
          <div class="card card-4">
            <img src="../../assets/img/blog4.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>To be number one, train like you’re number two</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
          <div class="card card-5">
            <img src="../../assets/img/trainer3.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>Top 5 mistakes every gym member makes</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
          <div class="card card-6">
            <img src="../../assets/img/trainer1.jpg" alt="" />
            <div class="card-text px-4 pb-4">
              <div class="card-title my-4">
                <h3>The myths of shedding body fat explored</h3>
              </div>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
                pretium, tortor vitae porttitor suscipit, sapien purus aliquet
                risus, eu finibus arcu ante nec risus. [...]
              </p>
            </div>
          </div>
        </div>
        <div class="btn-container d-flex justify-content-center p-4">
          <button>READ ALL ARTICLES</button>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.news {
  background-color: var(--primary-color);
  padding: 6rem 0;

  h2 {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
  }
  h3 {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
    font-size: 0.9375rem;
    color: #fff;
  }
  p {
    line-height: 1.8rem;
  }

  .cards-container {
    position: relative;
    height: 69rem;
  }

  .card {
    width: 32%;
    position: absolute;
    background-color: var(--secondary-color);
  }

  .card:hover {
    cursor: pointer;
    box-shadow: 0 0 5px 5px rgb(255, 255, 255);
    filter: sepia(100%);
  }

  .card-2 {
    left: 19rem;
  }

  .card-3 {
    right: 0;
  }

  .card-4 {
    top: 27.5rem;
  }

  .card-5 {
    left: 19rem;
    top: 36rem;
  }
  .card-6 {
    right: 0;
    top: 31.5rem;
  }
}
</style>
