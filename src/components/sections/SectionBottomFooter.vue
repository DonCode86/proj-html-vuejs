<template>
  <div class="container">
    <section class="bottom-footer">
      <div class="inner-container">
        <div class="row">
          <div class="col-9">
            <p>
              © Copyright 2012 - 2020 | Avada Theme by Theme Fusion | All Rights
              Reserved | Powered by WordPress
            </p>
          </div>
          <div class="col-3">
            <div class="social-container">
              <div class="socials d-flex justify-content-end">
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
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.bottom-footer {
  background-color: #000;
  padding: 2rem 0;
  & p {
    font-size: 0.7rem;
    margin: 0;
  }
  .social-icon {
    background-color: #ee6059;
    width: 1.875rem;
    height: 1.875rem;
    padding: 0.625rem;
    margin-right: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
  }
}
</style>
