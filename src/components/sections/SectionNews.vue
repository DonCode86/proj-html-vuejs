<template>
  <div class="container">
    <section class="news">
      <div class="inner-container">
        <div class="section-title">
          <h2 class="text-white text-center">PERFORMANCE NEWS</h2>
        </div>
        <div class="divider text-center py-3">
          <img
            class="image_img"
            src="../../assets/img/divider-xx-red.png"
            alt=""
          />
        </div>
        <div class="cards-container">
          <div class="card">
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/blog1-200x104.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/blog6.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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
          <div class="card card-3">
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/trainer4.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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
          <div class="card card-4">
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/blog4.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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
          <div class="card card-5">
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/trainer3.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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
          <div class="card card-6">
            <div class="img-container">
              <img
                class="content-image"
                src="../../assets/img/trainer1.jpg"
                alt=""
              />
              <div class="image__overlay text-white text-center">
                <i class="fa-solid fa-link p-2"></i>
                <i class="fa-solid fa-magnifying-glass p-2"></i>
              </div>
            </div>
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

  .img-container img {
    width: 100%;
  }

  .card {
    width: 32%;
    position: absolute;
    background-color: var(--secondary-color);
  }

  // .card:hover {
  //   cursor: pointer;
  //   box-shadow: 0 0 5px 5px rgb(255, 255, 255);
  //   filter: grayscale(100%);
  // }

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

  .img-container {
    position: relative;
    width: 100%;
  }

  .image__img {
    display: block;
    width: 100%;
  }

  .image__overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(239, 55, 55, 0.6);
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    font-size: 1.2rem;
    transition: opacity 0.4s;
  }
  .image__overlay > * {
    transform: translateY(20px);
    transition: transform 0.4s;
  }

  .image__overlay:hover > * {
    transform: translateY(0);
  }
  .image__overlay:hover {
    opacity: 1;
    cursor: pointer;
  }
}
</style>
