<template>
  <div class="best-sale d-flex flex-column align-items-center">
    <h1 class="text-center">สินค้าขายดี</h1>
    <div class="cards m-5 d-flex justify-content-evenly flex-wrap">
      <div class="card" v-for="(item, index) in bestItems" :key="index">
        <span
          v-if="item.sale"
          class="position-absolute text-light bg-danger px-1"
          >-{{ item.sale }}%</span
        >
        <div class="img-content"></div>
        <img :src="item.img" class="mb-2" />
        <div class="content-text m-3">
          <p>{{ item.brand }}</p>
          <h6>{{ item.detail }}</h6>
          <div v-if="item.sale" class="d-flex">
            <h6 class="fw-semibold text-danger">{{ item.salePrice }} ฿</h6>
            <span class="full-price ms-2 text-secondary"
              >{{ item.price }} ฿</span
            >
          </div>
          <div v-else>
            <h6 class="fw-semibold">{{ item.price }} ฿</h6>
          </div>

          <p class="text-secondary">{{ item.shop }}</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: "BestSellVue",
  components: {},
  data() {
    return {
      bestItems: [
        {
          brand: "vue3",
          img: require("../../assets/img/bs-1.jpg"),
          detail: "กระโปรงกางเกงดีไซน์ทบหน้า",
          price: 1500,
          shop: "vue",
          sale: 10,
          salePrice: 1350,
        },
        {
          brand: "vue x bootstrap5",
          img: require("../../assets/img/bs-2.jpg"),
          detail: "เดรสคล้องคอแต่งดีไซน์",
          price: "1200",
          shop: "bootstrap5",
          sale: "",
          salePrice: "",
        },
        {
          brand: "vue3",
          img: require("../../assets/img/bs-3.jpg"),
          detail: "เสื้อเชิ้ตดีไซน์คัตเอาท์สามเหลี่ยม",
          price: 1700,
          shop: "vue",
          sale: 20,
          salePrice: 1360,
        },
        {
          brand: "vue2",
          img: require("../../assets/img/bs-4.jpg"),
          detail: "เดรสคล้องคอแต่งดีไซน์",
          price: 1299,
          shop: "vue2",
          sale: "",
          salePrice: "",
        },
        {
          brand: "vue",
          img: require("../../assets/img/bs-5.jpg"),
          detail: "เสื้อเชิ้ตดีไซน์คัตเอาท์สามเหลี่ยม",
          price: 1599,
          shop: "vue2",
          sale: 10,
          salePrice: 1439,
        },
        {
          brand: "vue x bootstrap5",
          img: require("../../assets/img/bs-6.jpg"),
          detail: "เดรสคล้องคอแต่งดีไซน์",
          price: "1200",
          shop: "bootstrap5",
          sale: "",
          salePrice: "",
        },
        {
          brand: "vue3",
          img: require("../../assets/img/bs-2.jpg"),
          detail: "เสื้อเชิ้ตดีไซน์คัตเอาท์สามเหลี่ยม",
          price: 1700,
          shop: "vue",
          sale: 20,
          salePrice: 1360,
        },
        {
          brand: "vue x bootstrap5",
          img: require("../../assets/img/bs-8.jpg"),
          detail: "เดรสคล้องคอแต่งดีไซน์",
          price: "1200",
          shop: "bootstrap5",
          sale: "",
          salePrice: "",
        },
      ],
    };
  },
};
</script>
<style scoped>
.cards {
  width: 1400px;
  overflow: auto;
}
.card {
  width: 300px;
  height: 580px;
  overflow: hidden;
  margin: 0.5rem;
}
.card .img {
  width: 300px;
}
p,
h6 {
  line-height: 0.9;
}
h6 {
  font-size: 20px;
}
.full-price {
  text-decoration: line-through;
  text-align: center;
  font-size: 15px;
}
img:hover {
  width: 300px;
}
</style>
