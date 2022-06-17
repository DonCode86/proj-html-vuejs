<template>
  <div class="container">
    <section class="top-footer">
      <div class="inner-container">
        <div class="row">
          <div class="col-3">
            <div class="col-title">
              <h4>COME FIND US</h4>
            </div>
            <div class="info">
              <p>
                12345 North Main Street <br />
                <span> York, NY 555555</span> <br />
                <span>Phone: 1.800.555.6789</span><br />
                <span>Email:info@your-domain.com</span><br />
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="col-title">
              <h4>RECENT POSTS</h4>
            </div>
            <div class="recent-posts">
              <p>> Train with free weights or your body weight?</p>
              <p class="y-borded">
                > Nutritional advice that will keep you training
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="col-title">
              <h4>OPENING TIMES</h4>
            </div>
            <div class="times">
              <p>
                Weekdays Monday - Friday <br />
                <span>09:00 - 19:00</span>
              </p>
              <p>
                Weekends Saturday - Sunday <br />
                <span>09:00 - 21:00</span>
              </p>
            </div>
          </div>
          <div class="col-3">
            <img src="../../assets/img/gym_ad-compressor-200x133.jpg" alt="" />
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
.top-footer {
  background-color: var(--secondary-color);
  padding: 4rem 0;
  h4,
  p {
    font-size: 0.8rem;
    line-height: 1.6rem;
  }

  .col-title {
    color: #6c777b;
    margin-bottom: 1.2rem;
  }
  .y-borded {
    border-top: 1px solid #aaa9a93c;
    border-bottom: 1px solid #aaa9a93c;
    padding: 0.5rem 0;
  }

  .times span {
    opacity: 0.5;
  }
}
</style>
