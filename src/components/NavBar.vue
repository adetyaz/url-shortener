<template>
  <header class="header">
    <div class="logo-box">
      <img src="../assets/images/logo.svg" alt="Logo" class="logo" />
    </div>
    <nav class="nav">
      <ul class="nav__items">
        <li class="nav__list"><a href="" class="nav__link">Features</a></li>
        <li class="nav__list"><a href="" class="nav__link">Pricing</a></li>
        <li class="nav__list"><a href="" class="nav__link">Resources</a></li>
      </ul>
      <ul class="nav__buttons">
        <li class="nav__list"><a href="" class="nav__link">Login</a></li>
        <li class="nav__list"><a href="" class="nav__btn">Sign Up</a></li>
      </ul>
    </nav>
  </header>
</template>
<style lang="scss" scoped>
.header {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo-box {
  position: absolute;
  top: 2rem;
  left: 4rem;
}
.logo {
  height: 5rem;
}
.nav {
  display: flex;
  &__list {
    list-style: none;
    display: inline-block;
    margin: 0 3rem;
  }
  &__link {
    text-decoration: none;
    color: hsl(257, 7%, 63%);
    cursor: pointer;
    font-size: 2rem;
  }
  &__btn {
    height: 3.5rem;
    width: 10rem;
    background-color: hsl(180, 66%, 49%);
    display: block;
    color: white;
    text-decoration: none;
    border-radius: 3rem;
    height: 3.5rem;
    padding: 1rem 3rem;
    transition: all 10ms ease-in-out;

    &:hover {
      box-shadow: 0 0 1rem rgba($color: #000000, $alpha: 0.5);
      transform: scale(1.01);
    }
  }
}
</style>
