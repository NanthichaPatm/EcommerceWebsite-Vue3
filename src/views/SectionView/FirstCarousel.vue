<template>
  <div class="first-carousel my-3 d-flex justify-content-center">
    <div
      id="carouselExampleDark"
      class="carousel carousel-dark slide"
      data-bs-ride="carousel"
      data-interval="500"
      data-pause="hover"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleDark"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleDark"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleDark"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleDark"
          data-bs-slide-to="3"
          aria-label="Slide 4"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="2000">
          <img
            src="@/assets/img/carousel-1.jpg"
            class="d-block w-100"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block bg-light mx-auto">
            <h5>สนุกไม่รู้จบ ครบทุกสไตล์แฟชั่น</h5>
            <button class="btn btn-dark">ช้อปเลย</button>
          </div>
        </div>

        <div class="carousel-item" data-bs-interval="2000">
          <img src="@/assets/img/carousel-3.jpg" class="d-block w-100" />
          <div class="carousel-caption d-none d-md-block text-start">
            <h1 class="text-light">@EcommerceSHOP.</h1>
            <p class="text-light">
              Some representative placeholder content for the third slide.
            </p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="@/assets/img/carousel-2.jpg" class="d-block w-100" />
          <div class="carousel-caption d-none d-md-block mb-5">
            <button class="btn btn-warning text-light fs-1">
              SHOPPING NOW!
            </button>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="@/assets/img/carousel-4.jpg" class="d-block w-100" />
          <div class="carousel-caption d-none d-md-block text-end text-light">
            <h2>Trend of bags Fashion !</h2>
            <p>Some representative placeholder content for the third slide.</p>
            <button class="btn btn-light">ช้อปเลย</button>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
export default {
  name: "FirstCarouselVue",
  components: {},
};
</script>
<style scoped>
.carousel {
  width: 90%;
}
.carousel-indicators button {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  margin-right: 5px;
  margin-left: 5px;
}
.carousel-item {
  height: 400px;
}
</style>
