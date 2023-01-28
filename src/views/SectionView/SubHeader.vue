<template>
  <div>
    <div class="mx-5 my-2">
      <ul class="header-tooltip d-flex flex-wrap">
        <li class="section-tooltip">
          <span class="title-tooltip"
            ><font-awesome-icon
              icon="fa-solid fa-location-dot"
              class="pe-1 text-secondary"
            />Location</span
          >

          <div class="content-tooltip position-absolute">
            <div>
              ไม่ต้องทำเรื่องคืนให้ยุ่งยาก! ใช้บริการ
              Tap.Try.Buy.และจ่ายแค่ชิ้นที่ชอบ
            </div>
            <a href="#"> คลิกดูรายละเอียด</a>
          </div>
        </li>
        <li class="section-tooltip">
          <span class="title-tooltip"
            ><font-awesome-icon
              icon="fa-solid fa-sack-dollar"
              class="pe-1 text-secondary"
            />Cashback</span
          >

          <div class="content-tooltip position-absolute">
            <div>
              รับ Cashback ทุกออเดอร์, ห้ามพลาด ในเวลาจำกัดเท่านั้น!
              สนุกกับการช้อปด้วยสิทธิพิเศษ ส่วนลดจากพาร์ทเนอร์ & อีกมากมาย!
            </div>
            <a href="#"> คลิกดูรายละเอียด</a>
          </div>
        </li>
        <li class="section-tooltip">
          <span class="title-tooltip"
            ><font-awesome-icon
              icon="fa-solid fa-tag"
              class="pe-1 text-secondary"
            />New item</span
          >

          <div class="content-tooltip position-absolute">
            <div>Sale พิเศษสำหรับ VIP, ส่วนลดจากพาร์ทเนอร์ & อีกมากมาย!</div>
            <a href="#"> คลิกดูรายละเอียด</a>
          </div>
        </li>
        <li class="section-tooltip">
          <span class="title-tooltip"
            ><font-awesome-icon
              icon="fa-solid fa-truck-fast"
              class="pe-1 text-secondary"
            />ส่งฟรีเมื่อช้อปครบ 990 บาท</span
          >

          <div class="content-tooltip position-absolute">
            <div>
              เราจัดส่งให้ฟรีไม่มีค่าใช้จ่าย! ได้รับสินค้ารวดเร็วทันใจ
              เมื่อช้อปครบ 990 บาท
            </div>
          </div>
        </li>
        <li class="section-tooltip">
          <span class="title-tooltip"
            ><font-awesome-icon
              icon="fa-solid fa-money-bills"
              class="pe-1 text-secondary"
            />บริการเก็บเงินปลายทาง</span
          >

          <div class="content-tooltip position-absolute">
            <div>
              ลูกค้าที่ไม่สะดวกชำระเงินด้วยบัตรเครดิต
              สามารถเลือกบริการเก็บเงินปลายทาง
              และชำระเงินกับพนักงานส่งสินค้าของเราเมื่อสินค้าถึงมือเรียบร้อยแล้ว
            </div>
          </div>
        </li>
        <li class="section-tooltip ms-auto">สนุกไม่รู้จบ ครบทุกสไตล์แฟชั่น</li>
      </ul>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: "SubHeaderVue",
  components: {},
};
</script>
<style scoped>
ul {
  list-style-type: none;
}
.section-tooltip {
  font-size: 12px;
  font-weight: 200;
  border: 1px;
  padding-right: 15px;
  z-index: 1;
}
.content-tooltip {
  width: 100px;
  font-size: 12px;
  font-weight: 300;
  display: none;
  background: rgba(255, 255, 255, 0.857);
  padding: 5px;
}
.title-tooltip:hover + .content-tooltip,
.content-tooltip:hover {
  display: block;
  border: 1px solid rgb(197, 192, 192);
  border-radius: 3px;
}
</style>
