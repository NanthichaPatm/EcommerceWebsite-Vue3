<template>
  <div class="announce">
    <p class="text-center pe-1">
      <strong>ดีล Pay Day: ลดสูงสุด 30%</strong>| ลุคใหม่!
    </p>
    <span>ช้อปเลย</span>
  </div>
</template>
<script>
export default {
  name: "AnnouceVue",
  components: {},
};
</script>

<style scoped>
.announce {
  background: var(--pink);
  color: white;
  font-weight: 200;
  font-size: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 2.5rem;
}
.announce p {
  margin-top: 1rem;
}
.announce span {
  font-size: 10px;
  font-weight: normal;
  border: 1px solid white;
  padding: 0px 5px;
  background: #fff;
  color: var(--pink);
  border-radius: 5px;
  vertical-align: middle;
}
</style>
