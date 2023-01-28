<template>
  <div>
    <div class="header bg-light">
      <nav class="nav d-flex align-item-center justify-content-between">
        <div class="header-NewArrive">
          <a
            href="#"
            class="dropdown-header d-flex align-items-center"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <span class="align-self-center">สินค้าใหม่ </span>
            <div class="dropdown-arrow">
              <font-awesome-icon
                icon="fa-solid fa-chevron-down"
                class="align-baseline"
              />
            </div>
          </a>
          <ul class="dropdown-menu border border-0 border-bottom py-3">
            <div
              class="dropdown-title px-3 mx-4 my-2 d-flex align-items-center"
            >
              <h6 class="m-0 pe-2">ของใหม่รายสัปดาห์</h6>
              <span class="align-self-bottom">Last Released Jan 12</span>
            </div>
            <div class="dropdown-section text-center px-5 mx-5">
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-1.jpg" /><br /><span
                      class="text-dark pe-1"
                      >ไอเท็มมาใหม่
                      <span class="text-secondary fw-light">(989)</span></span
                    >
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-2.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      บิวตี้ไอเท็ม
                      <span class="text-secondary fw-light">(1738)</span></span
                    >
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-3.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      ชุดออกกำลังกาย
                      <span class="text-secondary fw-light">(743)</span></span
                    >
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-4.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      รองเท้า
                      <span class="text-secondary fw-light">(1289)</span></span
                    >
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-5.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      เครื่องประดับทั้งหมด
                      <span class="text-secondary fw-light">(4194)</span></span
                    >
                  </a>
                </div>
              </li>
            </div>
          </ul>
        </div>
        <div class="header-Shop">
          <a
            href="#"
            class="dropdown-header d-flex align-items-center"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <span class="align-self-center">ช้อป </span>
            <div class="dropdown-arrow">
              <font-awesome-icon
                icon="fa-solid fa-chevron-down"
                class="align-baseline"
              />
            </div>
          </a>
          <ul class="dropdown-menu border border-0 border-bottom py-3">
            <div>
              <ul class="d-flex justify-content-evenly align-items-top">
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">เสื้อผ้าทั้งหมด</div>
                  <a href="#" class="text-dark fw-light">เสื้อผ้าทั้งหมด</a>
                  <a href="#" class="text-dark fw-light">สินค้าขายดี</a>
                  <a href="#" class="text-dark fw-light">ชุดเซ็ต</a>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เสื้อเบลาซ์</a>
                  <a href="#" class="text-dark fw-light">เสื้อ</a>
                  <a href="#" class="text-dark fw-light">เสื้อทีเชิ้ต</a>
                  <a href="#" class="text-dark fw-light">กางเกง & กระโปรง</a>
                  <a href="#" class="text-dark fw-light"
                    >กระโปรง & กางเกงขาสั้น</a
                  >
                </div>
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Dresses</div>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เดรสยาวคลุมเข่า</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">ช้อปไอเท็มตามโอกาสต่าง ๆ</div>
                  <a href="#" class="text-dark fw-light">เสื้อผ้าทั้งหมด</a>
                  <a href="#" class="text-dark fw-light">สินค้าขายดี</a>
                  <a href="#" class="text-dark fw-light">ชุดเซ็ต</a>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เสื้อ</a>
                </div>
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Accessories</div>
                  <a href="#" class="text-dark fw-light">เสื้อผ้าทั้งหมด</a>
                  <a href="#" class="text-dark fw-light">สินค้าขายดี</a>
                  <a href="#" class="text-dark fw-light">ชุดเซ็ต</a>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เสื้อเบลาซ์</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
              </ul>
            </div>
          </ul>
        </div>
        <div class="header-Feature">
          <a
            href="#"
            class="dropdown-header d-flex align-items-center"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <span class="align-self-center">ฟีเจอร์ </span>
            <div class="dropdown-arrow">
              <font-awesome-icon
                icon="fa-solid fa-chevron-down"
                class="align-baseline"
              />
            </div>
          </a>
          <ul class="dropdown-menu border border-0 border-bottom py-3">
            <div class="dropdown-section text-center px-5 mx-5">
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-1.jpg" /><br /><span
                      class="text-dark pe-1"
                      >Brands You Love.
                    </span>
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-2.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      สไตล์เป็นมิตรต่อสิ่งแวดล้อม.
                    </span>
                  </a>
                </div>
              </li>
              <li>
                <div class="link-a d-flex justify-content-center">
                  <a href="#"
                    ><img src="@/assets/img/header-3.jpg" /><br /><span
                      class="text-dark pe-1"
                    >
                      ไอเดียของขวัญ.
                    </span>
                  </a>
                </div>
              </li>
            </div>
          </ul>
        </div>
        <div class="header-Saleitem">
          <a
            href="#"
            class="dropdown-header d-flex align-items-center"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <span class="align-self-center">สินค้าลดราคา </span>
            <div class="dropdown-arrow">
              <font-awesome-icon
                icon="fa-solid fa-chevron-down"
                class="align-baseline"
              />
            </div>
          </a>
          <ul class="dropdown-menu border border-0 border-bottom py-3">
            <div>
              <ul class="d-flex justify-content-evenly align-items-top">
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Dresses</div>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เดรสยาวคลุมเข่า</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Accessories</div>
                  <a href="#" class="text-dark fw-light">เสื้อผ้าทั้งหมด</a>
                  <a href="#" class="text-dark fw-light">สินค้าขายดี</a>
                  <a href="#" class="text-dark fw-light">ชุดเซ็ต</a>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เสื้อเบลาซ์</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
              </ul>
            </div>
          </ul>
        </div>
        <div class="header-Brands">
          <a
            href="#"
            class="dropdown-header d-flex align-items-center"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            <span class="align-self-center"> Brands </span>
            <div class="dropdown-arrow">
              <font-awesome-icon
                icon="fa-solid fa-chevron-down"
                class="align-baseline"
              />
            </div>
          </a>
          <ul class="dropdown-menu border border-0 border-bottom py-3">
            <div>
              <ul class="d-flex justify-content-evenly align-items-top">
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Dresses</div>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เดรสยาวคลุมเข่า</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
                <div class="link-a d-flex flex-column mx-5">
                  <div class="mb-3 fs-5">Accessories</div>
                  <a href="#" class="text-dark fw-light">เสื้อผ้าทั้งหมด</a>
                  <a href="#" class="text-dark fw-light">สินค้าขายดี</a>
                  <a href="#" class="text-dark fw-light">ชุดเซ็ต</a>
                  <a href="#" class="text-dark fw-light">เดรส</a>
                  <a href="#" class="text-dark fw-light">เสื้อเบลาซ์</a>
                  <a href="#" class="text-dark fw-light">เดรสสั้น</a>
                  <a href="#" class="text-dark fw-light">เดรสสำหรับไปเที่ยว</a>
                </div>
                <div class="link-a mx-3">
                  <a href="#"
                    ><img
                      src="@/assets/img/header-5.jpg"
                      style="width: 280px; height: 90%"
                  /></a>
                </div>
                <div class="link-a d-flex flex-column" style="width: 310px">
                  <div>
                    <a href="#"><img src="@/assets/img/header-5.jpg" /></a>
                    <a href="#"><img src="@/assets/img/header-2.jpg" /></a>
                  </div>

                  <div>
                    <a href="#"><img src="@/assets/img/header-1.jpg" /></a>
                    <a href="#"><img src="@/assets/img/header-5.jpg" /></a>
                  </div>
                </div>
              </ul>
            </div>
          </ul>
        </div>
        <div class="header-LookBook link-a">
          <a href="#" class="text-dark align-self-center"
            ><span>LookBook</span></a
          >
        </div>
        <div class="header-Name mx-auto">
          <h3 class="pt-2 text-center">EcommerceSHOP.</h3>
        </div>
        <div class="header-End link-a ms-auto">
          <a href="#" class="text-dark align-self-center pe-3"
            ><span>ลงทะเบียน </span></a
          >
          <a href="#" class="text-dark align-self-center pe-3"
            ><span>เข้าสู่ระบบ</span></a
          >
          <span class="align-self-center text-secondary pe-3">|</span>
          <a href="#" class="text-dark align-self-center pe-3"
            ><span><font-awesome-icon icon="fa-solid fa-earth-americas" /></span
          ></a>
          <a href="#" class="text-dark align-self-center pe-3"
            ><span
              ><font-awesome-icon icon="fa-solid fa-magnifying-glass" /></span
          ></a>
          <a href="#" class="text-dark align-self-center pe-3"
            ><span><font-awesome-icon icon="fa-solid fa-bag-shopping" /></span
          ></a>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "HeaderVue",
  components: {},
};
</script>
<style scoped>
.header nav {
  font-weight: 300;
  font-size: 12px;
  padding: 10px;
  margin: 0px 50px;
  border-bottom: 1px solid var(--lightGray);
}
.header nav div {
  display: flex;
  font-size: 14px;
  margin: 0px 6px;
}
img {
  width: 90%;
  height: 90%;
}
.header nav a .dropdown-arrow {
  transition: 0.5s;
}
.header nav .dropdown-header {
  text-decoration: none;
}
.header nav a:focus {
  outline: none;
}
.header nav a:focus-within .dropdown-arrow {
  transform: rotate(180deg);
}
.header nav a:hover {
  color: black;
}
.dropdown-menu {
  width: 100%;
}
.dropdown-title span:nth-last-child(1) {
  font-size: smaller;
  font-weight: 300;
  color: var(--lightGray);
  padding-top: 2px;
}
.link-a a {
  text-decoration: none;
}
.link-a a:hover {
  text-decoration: underline;
}
/* end-header */
.header-End a span:hover {
  color: var(--pink);
}
</style>
