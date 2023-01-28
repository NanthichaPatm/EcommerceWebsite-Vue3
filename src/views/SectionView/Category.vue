<template>
  <div class="category my-5">
    <div class="d-flex justify-content-center align-items-center m-3 flex-wrap">
      <div class="text-content align-self-center text-center me-5 px-5">
        <h5>ลด 20% ทั้งเว็บ ทุกไอเท็ม</h5>
        <h5>เมื่อช้อปออเดอร์แรก! | โค้ด: OMG20TH ไม่มีขั้นต่ำ</h5>
        <h5>+ รับ CASHBACK เมื่อสมัครสมาชิก</h5>
        <h5>ช้อปดีลสุดปังเลย</h5>
      </div>
      <div>
        <a href="#" class="ms-5"
          ><h1 class="text-img text-light">เสื้อ.</h1>
          <img src="@/assets/img/category-1.jpg" class="ms-4" />
        </a>
      </div>
    </div>
    <div class="d-flex justify-content-center align-items-center m-3 flex-wrap">
      <div>
        <a href="#" class="m-4"
          ><h1 class="text-img text-light">
            กระโปรง <br />
            และกางเกง.
          </h1>
          <img src="@/assets/img/category-4.jpg" class="m-4" />
        </a>
      </div>
      <div>
        <a href="#" class="m-4"
          ><h1 class="text-img text-light ps-5 ms-5">เดรส.</h1>
          <img src="@/assets/img/category-2.jpg" class="m-4" />
        </a>
      </div>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src

export default {
  name: "CategoryVue",
  components: {},
};
</script>
<style scoped>
img {
  width: 500px;
  height: 650px;
}
.text-img {
  position: absolute;
  margin-top: 13rem;
  margin-left: 13rem;
}
</style>
