<template>
  <div>
    <div class="short-detail">
      <div class="bg-dark d-flex align-items-stretch">
        <span class="text-light"
          ><div><font-awesome-icon icon="fa-solid fa-sack-dollar" /></div>
          <h5>VueClub</h5>
          <p>รับ Cashback ทุกออเดอร์</p></span
        >
        <span class="text-light"
          ><div><font-awesome-icon icon="fa-solid fa-tag" /></div>
          <h5>สินค้าใหม่</h5>
          <p>รายสัปดาห์</p></span
        >
        <span class="text-light"
          ><div><font-awesome-icon icon="fa-solid fa-truck-fast" /></div>
          <h5>ส่งฟรี</h5>
          <p>เมื่อช้อปครบ 990 บาท</p></span
        >
        <span class="text-light"
          ><div><font-awesome-icon icon="fa-solid fa-money-bills" /></div>
          <h5 class="pt-4">บริการเก็บเงินปลายทาง</h5>
        </span>
      </div>
    </div>
    <div class="footer my-2">
      <div class="d-flex align-items-stretch">
        <span class="footer text-start">
          <ul>
            EcommerceSHOP.
            <li>สนุกไม่รู้จบ ครบทุกสไตล์แฟชั่น</li>
          </ul>
        </span>
        <span class="footer text-start">
          <ul>
            Info
            <li>About us</li>
            <li>ติดต่อเรา</li>
            <li>ข่าวประชาสัมพันธ์</li>
            <li>แนะนำเพื่อน</li>
          </ul>
        </span>
        <span class="footer text-start">
          <ul>
            Help
            <li>การส่งสินค้า</li>
            <li>การคืนสินค้า</li>
            <li>คำถามที่พบบ่อย</li>
          </ul>
        </span>
        <span class="footer text-start">
          <ul>
            Contact
            <li>Vue3+Bootstrap5</li>
            <li class="fs-2">
              <font-awesome-icon
                icon="fa-brands fa-facebook"
                class="px-2"
              /><font-awesome-icon
                icon="fa-brands fa-instagram"
                class="px-2"
              /><font-awesome-icon
                icon="fa-brands fa-github"
                class="px-2"
              /><font-awesome-icon icon="fa-brands fa-linkedin" class="px-2" />
            </li>
          </ul>
        </span>
      </div>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: "FooterVue",
  components: {},
};
</script>
<style scoped>
span {
  padding-top: 1rem;
  border: 1px solid white;
  width: 25%;
  text-align: center;
  padding: 10px;
}
p {
  font-weight: 200;
}
span div {
  font-size: 30px;
}
ul {
  list-style-type: none;
  font-weight: 300;
}
li {
  font-size: 13px;
  font-weight: 200;
  cursor: pointer;
}
</style>
