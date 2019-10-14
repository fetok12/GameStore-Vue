<template>
  <div class="carousel container">
    <div class="title">
      <i class="fab fa-gg-circle"></i>
      <span class="ml-2">Separate 1</span>
      <hr>
    </div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide img-src="https://i.ytimg.com/vi/m3yThoH_iXQ/maxresdefault.jpg">
        <h4 style="float:left">SQUAD: Yeni Macera</h4>
        <div style="float:right; ">
          <div id="card">
            <i class="fas fa-shopping-cart mr-2"></i>
            <span>Sepete Ekle</span>
          </div>
          <div id="secondCard">29,50 Ł</div>
          <div id="thirdCard">-%90</div>
        </div>
      </b-carousel-slide>
      <b-carousel-slide img-src="https://wallpapersite.com/images/pages/pic_w/307.jpg">
        <h4 style="float:left">SQUAD: Yeni Macera</h4>
        <div style="float:right; ">
          <div id="card">
            <i class="fas fa-shopping-cart mr-2"></i>
            <span>Sepete Ekle</span>
          </div>
          <div id="secondCard">29,50 Ł</div>
          <div id="thirdCard">-%90</div>
        </div>
      </b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.coolridged.com/wp-content/uploads/2018/06/wZFo6e0t7hQ.jpg"
      >
        <h4 style="float:left">SQUAD: Yeni Macera</h4>
        <div style="float:right; ">
          <div id="card">
            <i class="fas fa-shopping-cart mr-2"></i>
            <span>Sepete Ekle</span>
          </div>
          <div id="secondCard">29,50 Ł</div>
          <div id="thirdCard">-%90</div>
        </div>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "Carousel",
  data() {
    return {
      slide: 0,
      sliding: null
    };
  },
  methods: {}
};
</script>

<style scoped>
.title {
  padding: 40px 0 0px 0;
}
.title span {
  font-weight: 500;
}
.header {
  color: #fff;
  text-align: center;
  padding: 50px;
}
.carousel {
}
#card {
  padding: 15px;
  background-color: #231f20;
  float: right;
  border-radius: 4px;
}
#secondCard {
  padding: 10px 15px 10px 15px;
  float: right;
  font-size: 22px;
}
#thirdCard {
  padding: 10px 15px 10px 15px;
  background-color: #d71920;
  float: right;
  border-radius: 4px;
  font-size: 22px;
}
.header a {
  color: #fff;
  padding-right: 5px;
  text-decoration: none;
}

hr {
  border-top: 2px solid #a6a6a6;
}
</style>


