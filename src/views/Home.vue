<template>
  <main>
    <section class="hero-section">
      <div class="hero">
        <div class="hero__text-content">
          <h1 class="heading__primary">
            More than just shorter links
          </h1>
          <p class="paragraph__primary">
            Build your brand's recognition and get detailed insights on how your
            links are performing
          </p>
          <a href="" class="btn-hero">Get Started</a>
        </div>
        <div class="hero__image-content">
          <img
            src="../assets/images/illustration-working.svg"
            alt="working"
            class="hero__image"
          />
        </div>
      </div>
    </section>
    <div class="form">
      <input type="text" class="form__input" />
      <a href="" class="form__button" type="submit">Shorten It! </a>
    </div>
    <section class="features-section">
      <h3 class="heading__secondary">Advanced Statistics</h3>
      <p class="paragraph__secondary">
        Track how your links are performing across the web with our advanced
        statistics dashboard
      </p>
      <div class="features">
        <div class="features__card">
          <img
            src="../assets/images/icon-brand-recognition.svg"
            alt=""
            class="features__icon"
          />
          <h3 class="features__title">Brand Recognition</h3>
          <p class="features__text">
            Build your recognition with each click. Generic links don't mean a
            thing. Branded links help instill confidence in your content
          </p>
        </div>
        <div class="features__card">
          <img
            src="../assets/images/icon-detailed-records.svg"
            alt=""
            class="features__icon"
          />
          <h3 class="features__title">Detailed Records</h3>
          <p class="features__text">
            Gain insights into who is clicking your links. Knowing when and
            where people engage with your content helps inform better decisions
          </p>
        </div>
        <div class="features__card">
          <img
            src="../assets/images/icon-fully-customizable.svg"
            alt=""
            class="features__icon"
          />
          <h3 class="features__title">Fully Customizable</h3>
          <p class="features__text">
            Improve brand awareness and content discoverability through
            customizable links, supercharging audience engagement
          </p>
        </div>
      </div>
    </section>
    <section class="cta-section">
      <div class="cta">
        <h3 class="heading__secondary">Boost your links</h3>
        <a href="" class="btn-hero">Get Started</a>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Home"
};
</script>
<style lang="scss" scoped>
.hero-section {
  background-color: white;
  padding: 9rem 0;
  padding-left: 15rem;
  overflow: hidden;
}
.hero {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  &__image {
    height: 45rem;
    margin-right: -13rem;
  }
  &__text-content {
    flex: 0 0 40%;
  }
}

.heading {
  &__primary {
    font-size: 5rem;
    font-weight: 700;
    color: hsl(260, 8%, 14%);
  }
  &__secondary {
    font-size: 2rem;
    font-weight: 700;
    color: hsl(260, 8%, 14%);
    text-align: center;
  }
}

.paragraph {
  &__primary {
    font-size: 2rem;
    font-weight: 500;
    color: hsl(260, 8%, 14%);
  }
  &__secondary {
    font-size: 1.8rem;
    font-weight: 500;
    color: hsl(260, 8%, 14%);
    text-align: center;
  }
}

.btn-hero {
  height: 4rem;
  width: 15rem;
  background-color: hsl(180, 66%, 49%);
  color: white;
  display: block;
  font-size: 1.8rem;
  text-decoration: none;
  border-radius: 3rem;
  padding: 0.4rem 3rem;
  transition: all 10ms ease-in-out;
  &:hover {
    box-shadow: 0 0 1rem rgba($color: #000000, $alpha: 0.5);
    transform: scale(1.01);
  }
}
.form {
  height: 15rem;
  width: 70vw;
  background: url("../assets/images/bg-shorten-desktop.svg"), #3b3054;
  background-size: cover;
  padding: 6rem 0rem;
  position: relative;
  left: 18rem;
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  &__input {
    height: 5rem;
    width: 40%;
    padding: 0 1.5rem;
    font-size: inherit;
    font-family: inherit;
    outline: none;
    border: none;
    border-radius: 0.5rem;

    &:focus {
      border: 1px solid rgb(22, 248, 2);
    }
  }
  &__button {
    height: 5rem;
    width: 15rem;
    background-color: hsl(180, 66%, 49%);
    color: white;
    display: block;
    font-size: 1.8rem;
    text-decoration: none;
    border-radius: 0.3rem;
    padding: 0.4rem 3rem;
    transition: all 10ms ease-in-out;
    &:hover {
      box-shadow: 0 0 1rem rgba($color: #000000, $alpha: 0.5);
      transform: scale(1.01);
    }
  }
}
</style>
