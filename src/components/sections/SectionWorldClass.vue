<template>
  <div class="container">
    <section class="world__class d-flex justify-content-center">
      <div class="inner-container">
        <div
          class="row d-flex text-center p-5 justify-content-center text-white"
        >
          <h3>WORLD CLASS Fitness</h3>
          <img class="py-4" src="../../assets/img/divider-xx-red.png" alt="" />
          <p class="py-1 px-4">
            At Avada Gym, everything we do from top to bottom is of the highest
            quality to ensure we're equipped to help you reach your goals of a
            healthy and fit lifestyle.
          </p>
        </div>
      </div>
      <div class="triangle-down"></div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.world__class {
  background-color: var(--primary-color);
  padding: 3rem 0;
  position: relative;

  & img {
    width: 3.125rem;
  }

  & h3 {
    font-weight: 800;
  }

  .triangle-down {
    width: 0;
    height: 0;
    border-left: 90px solid transparent;
    border-right: 90px solid transparent;
    border-top: 100px solid var(--primary-color);
    position: absolute;
    bottom: -2rem;
    z-index: 10;
  }
}
</style>
