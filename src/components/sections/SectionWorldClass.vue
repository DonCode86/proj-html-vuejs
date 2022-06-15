<template>
  <div class="container">
    <section class="world__class">
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

  & img {
    width: 3.125rem;
  }

  & h3 {
    font-weight: 800;
  }
}
</style>
