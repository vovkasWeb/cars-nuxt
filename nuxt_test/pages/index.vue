<template>
  <section class="main">
    <div class="container">
      <div class="main__inner">
        <div class="language">
          <NuxtLink class="language-lint" to="/"> Англиский</NuxtLink>
          <NuxtLink class="language-lint" to="/it">
            Итальянский
          </NuxtLink>
        </div>
        <h1>{{ $t("main.cars") }}</h1>

        <div class="main__body">
          <div class="main__item">
            <img
              class="main__img-item"
              src="~/assets/01683670945_file.jpg"
              alt=""
            />
            <div class="main__body-item">
              <div class="main__price-item main__points-item">
                <span>{{ $t("main.price") }}</span> <span>50000 USD</span>
              </div>
              <div class="main__code-item main__points-item">
                <span>{{ $t("main.code") }}</span> <span>256767</span>
              </div>
              <div class="main__country-item main__points-item">
                <span>{{ $t("main.country") }}</span> <span>Ukraine</span>
              </div>
              <div class="main__probeg-item main__points-item">
                <span>{{ $t("main.probeg") }}</span> <span>150</span>
              </div>
              <div class="main__l-item main__points-item">
                <span>{{ $t("main.l") }}</span> <span>3l</span>
              </div>
            </div>
          </div>

          <div class="main__item">
            <img
              class="main__img-item"
              src="~/assets/01683670945_file.jpg"
              alt=""
            />
            <div class="main__body-item">
              <div class="main__price-item main__points-item">
                <span>{{ $t("main.price") }}</span> <span>50000 USD</span>
              </div>
              <div class="main__code-item main__points-item">
                <span>{{ $t("main.code") }}</span> <span>256767</span>
              </div>
              <div class="main__country-item main__points-item">
                <span>{{ $t("main.country") }}</span> <span>Ukraine</span>
              </div>
              <div class="main__probeg-item main__points-item">
                <span>{{ $t("main.probeg") }}</span> <span>150</span>
              </div>
              <div class="main__l-item main__points-item">
                <span>{{ $t("main.l") }}</span> <span>3l</span>
              </div>
            </div>
          </div>

          <div class="main__item">
            <img
              class="main__img-item"
              src="~/assets/01683670945_file.jpg"
              alt=""
            />
            <div class="main__body-item">
              <div class="main__price-item main__points-item">
                <span>{{ $t("main.price") }}</span> <span>50000 USD</span>
              </div>
              <div class="main__code-item main__points-item">
                <span>{{ $t("main.code") }}</span> <span>256767</span>
              </div>
              <div class="main__country-item main__points-item">
                <span>{{ $t("main.country") }}</span> <span>Ukraine</span>
              </div>
              <div class="main__probeg-item main__points-item">
                <span>{{ $t("main.probeg") }}</span> <span>150</span>
              </div>
              <div class="main__l-item main__points-item">
                <span>{{ $t("main.l") }}</span> <span>3l</span>
              </div>
            </div>
          </div>

          <div class="main__item">
            <img
              class="main__img-item"
              src="~/assets/01683670945_file.jpg"
              alt=""
            />
            <div class="main__body-item">
              <div class="main__price-item main__points-item">
                <span>{{ $t("main.price") }}</span> : <span>50000 USD</span>
              </div>
              <div class="main__code-item main__points-item">
                <span>{{ $t("main.code") }}</span> : <span>256767</span>
              </div>
              <div class="main__country-item main__points-item">
                <span>{{ $t("main.country") }}</span> : <span>Ukraine</span>
              </div>
              <div class="main__probeg-item main__points-item">
                <span>{{ $t("main.probeg") }}</span> : <span>150</span>
              </div>
              <div class="main__l-item main__points-item">
                <span>{{ $t("main.l") }}</span> : <span>3l</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import MainBody from "../components/MainBody.vue";
export default {
  components: { MainBody },
  name: "IndexPage",
};
</script>
<style scoped>
.main__inner {
  padding: 10px 0;
}

.nuxt-link-exact-active {
  color: #df0000;
}
.main__body {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.main__item {
  padding: 5px;
  flex: 0 1 48%;
}
.main__img-item {
  width: 100%;
}
.main__points-item {
  font-size: 24px;
}
</style>
