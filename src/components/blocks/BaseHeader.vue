<template>
  <div class="container">
    <header class="header">
      <div class="container">
        <div
          class="header-top d-flex align-items-center justify-content-between mt-2"
        >
          <div class="header__logo">
            <img src="../../assets/img/gym_logo_1x.png" alt="" />
          </div>
          <div class="nav-bar">
            <ul class="text-white d-flex list-unstyled gap-4">
              <li
                v-for="(link, index) in links"
                :key="index"
                :class="{ active: link.current }"
              >
                <a>{{ link.text }}</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
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
  data() {
    return {
      links: [
        {
          text: "HOME",
          href: "#",
          current: true,
        },
        {
          text: "ABOUT US",
          href: "#",
          current: false,
        },
        {
          text: "FACILITIES",
          href: "#",
          current: false,
        },
        {
          text: "MEMBERSHIP",
          href: "#",
          current: false,
        },
        {
          text: "TESTIMONIALS",
          href: "#",
          current: false,
        },
        {
          text: "BLOG",
          href: "#",
          current: false,
        },
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
.header {
  background-color: #121314;
  padding: 1.875rem 4.5rem;
  background-image: url(../../assets/img/home-banner.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 0 -2rem;
  min-height: 40rem;

  &__logo img {
    width: 9rem;
  }

  .nav-bar a {
    font-size: 0.7rem;
    cursor: pointer;
  }
  .nav-bar a:hover {
    color: #ee6059;
  }

  .active a {
    color: #ee6059;
  }

  .hero__text {
    text-align: center;
    vertical-align: middle;
    padding-top: 8.2rem;
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
