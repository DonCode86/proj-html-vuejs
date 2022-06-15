<template>
  <div class="container">
    <header class="header">
      <div class="container">
        <div class="row">
          <div class="header__logo">
            <img src="../../assets/img/gym_logo_1x.png" alt="" />
          </div>
        </div>
      </div>
      <div class="header__nav"></div>
      <div class="hero__text">
        <h1>NO PAIN NO GAIN</h1>
        <p>
          Motivation is what gets you started. Habit is what keeps you going.
        </p>
        <button class="mt-2">JOIN US TODAY</button>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "BaseHeader",
}
</script>

<style lang="scss" scoped>
.header {
  background-color: #121314;
  padding: 1.875rem 4.5rem;
  background-image: url(../../assets/img/home-banner.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 0 -2.5rem;
  min-height: 43.75rem;

  &__logo img {
    width: 9rem;
  }

  .hero__text {
    text-align: center;
    vertical-align: middle;
    padding-top: 7.7rem;
    color: white;

    & h1 {
      font-size: 4.375rem;
      font-weight: 700;
    }

    & p {
      font-size: 0.875rem;
      color: #fff;
    }

    & button {
      font-size: 0.875rem;
      padding: 0.425rem 1.2rem;
      background: transparent;
      color: white;
      border-color: white;
      opacity: 0.6;
    }
  }
}
</style>
