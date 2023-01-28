<template>
  <div class="home">
    <AnnounceVue />
    <HeaderVue class="sticky-top" />
    <SubHeaderVue />
    <FirstCarouselVue />
    <CategoryVue />
    <BestSellVue />
    <FooterVue />

    <div class="stick-ads">
      <div class="fixed-bottom mb-1">
        <span class="text-light d-flex flex-column">
          <span class="title">ดาวน์โหลดแอพ!</span>
          <span class="section"><img src="../assets/img/qrcode.jpg" /></span>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import AnnounceVue from "@/views/SectionView/Announce.vue";
import HeaderVue from "@/views/SectionView/Header.vue";
import SubHeaderVue from "@/views/SectionView/SubHeader.vue";
import FirstCarouselVue from "@/views/SectionView/FirstCarousel.vue";
import CategoryVue from "@/views/SectionView/Category.vue";
import BestSellVue from "@/views/SectionView/BestSell.vue";
import FooterVue from "@/views/SectionView/Footer.vue";

export default {
  name: "HomeView",
  components: {
    AnnounceVue,
    HeaderVue,
    SubHeaderVue,
    FirstCarouselVue,
    CategoryVue,
    BestSellVue,
    FooterVue,
  },
};
</script>
<style scoped>
.title {
  margin: 1rem;
  background: var(--pink);
  padding: 1rem;
  vertical-align: top;
  border-radius: 50%;
  opacity: 85%;
  width: 135px;
}
.section img {
  width: 100px;
  border-radius: 5px;
  margin-left: 2.3rem;
  border: 10px solid var(--pink);
  display: none;
}
.title:hover + .section img,
img:hover {
  display: block;
}
</style>
