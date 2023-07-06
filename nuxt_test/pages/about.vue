<template>
  <section class="about">
    <div class="container">
      <div class="language">
        <NuxtLink class="language-lint" to="/about"> Англиский</NuxtLink>
        <NuxtLink class="language-lint" to="/it/about"> Итальянский </NuxtLink>
      </div>
      <h1 class="about__title">{{ $t("about.avtosalon") }}</h1>
      <p class="about__text">{{ $t("about.info") }}</p>
      <p class="about__text">{{ $t("about.infoavtosalon.oblasti") }}</p>
      <p class="about__text">{{ $t("about.infoavtosalon.citi") }}</p>
      <p class="about__text">{{ $t("about.infoavtosalon.address") }}</p>
    </div>
  </section>
</template>

<script>
export default {
  nuxtI18n: {
    paths: {
      it: "it/about/",
      en: "/about",
    },
  },
};
</script>

<style scoped>
.nuxt-link-exact-active {
  color: #df0000;
}
.about__title {
  font-size: 45px;
}
.about__text {
  font-size: 36px;
  text-align: center;
}
</style>
