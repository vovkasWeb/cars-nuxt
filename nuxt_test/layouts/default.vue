<template>
  <div>
    <div class="header">
      <div class="container">
        <div class="header__line">
          <a class="header__logo" href="/">
            <img
              class="header__logo-img"
              src="~/assets/pngfind.com-cars-logo-png-628287.png"
              alt=""
            />
          </a>
          <nav class="menu">
            <NuxtLink class="menu__link" to="/">Главная страница</NuxtLink>
            <NuxtLink class="menu__link" to="/about"> Про нас</NuxtLink>
          </nav>
        </div>
      </div>
    </div>
    <nuxt />
  </div>
</template>

<style scoped>
.header {
  padding: 10px 0;
  background-color: rgb(135, 135, 12);
}
.header__line {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header__logo-img {
  max-width: 300px;
}
.menu__link {
  font-size: 36px;
  margin: 0 5px;
  color: #4603d7;
  text-decoration: none !important;
}
.nuxt-link-exact-active {
  color: #df0000;
}
</style>
