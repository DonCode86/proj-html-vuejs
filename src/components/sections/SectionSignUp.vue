<template>
  <div class="container">
    <section class="section-signup">
      <div class="inner-container">
        <div class="row g-4">
          <div class="col-6">
            <img
              class="img-fluid"
              src="../../assets/img/home_img-compressor.jpg"
              alt=""
            />
          </div>
          <div class="col-6">
            <h3 class="text-white">Sign Up For A Free Training Session!</h3>
            <div class="input-container mt-5">
              <p class="mb-1">Name..*</p>
              <input
                type="text"
                class="text-input"
                ng-model="text"
                placeholder=""
                style="display: block; width: 100%"
              />
              <p class="mb-1 mt-4">Email</p>
              <input
                type="text"
                class="text-input mb-4"
                ng-model="text"
                placeholder=""
                style="display: block; width: 100%"
              />
              <button class="mt-2">START NOW!</button>
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
.section-signup {
  padding: 6rem 0;
  background-color: var(--secondary-color);

  & h3 {
    font-weight: 800;
    font-size: 1.125rem;
  }

  input {
    background-color: #202325;
    border: 1px solid #3e4346;
  }

  button {
    width: 100%;
    background-color: #ee6059;
    opacity: 1;
    border: none;
    padding: 0.6rem 1.2rem;
  }
}
</style>
