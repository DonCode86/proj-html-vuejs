<template>
  <div class="container">
    <section class="bruce-lee">
      <div class="inner-container">
        <div class="section-text text-center text-white">
          <h3>
            " I fear not man who has practiced 10,000 kicks once, but i fear the
            man who has practiced one kick 10,000 times "
          </h3>
          <strong>BRUCE LEE • QUOTE OF THE DAY </strong>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.bruce-lee {
  background-image: url("../../assets/img/home-testimonial-bg.jpg");
  background-size: cover;
  background-position: center;
  .section-text {
    padding: 10rem 7rem;
    font-size: 18px;
    font-weight: 500;
    letter-spacing: 0.125rem;

    & h3 {
      font-size: 1.875rem;
      padding-bottom: 3.5rem;
    }
  }
}
</style>
