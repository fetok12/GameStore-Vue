<template>
  <div class="container">
    <div class="headerTitle">
      <i class="fab fa-gg-circle"></i>
      <span class="ml-2">Submission</span>
      <hr>
    </div>
    <md-card>
      <md-card-media>
        <!-- swiper -->
        <swiper :options="swiperOption">
          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://biteable.com/content/uploads/2018/07/Best-Commercials-S-1280x995.55555555556-c-default.jpg"
              alt
            >
          </swiper-slide>
          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://cached.imagescaler.hbpl.co.uk/resize/scaleWidth/580/cached.offlinehbpl.hbpl.co.uk/news/NST/Twitter_Logo_WhiteOnBlue-20190122114927359.jpg"
              alt
            >
          </swiper-slide>

          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://pbs.twimg.com/profile_images/788661847448838144/N59Ac7x-_400x400.jpg"
              alt
            >
          </swiper-slide>
          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-nALILZYQFYoSWgPDnpS2B-01vde3UWcBt0NlhUH46_JUxyMeXQ"
              alt
            >
          </swiper-slide>
          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://s.marketwatch.com/public/resources/images/MW-HB714_master_ZH_20190110080409.jpg"
              alt
            >
          </swiper-slide>
          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://cached.imagescaler.hbpl.co.uk/resize/scaleWidth/580/cached.offlinehbpl.hbpl.co.uk/news/NST/Twitter_Logo_WhiteOnBlue-20190122114927359.jpg"
              alt
            >
          </swiper-slide>

          <swiper-slide>
            <img
              width="250"
              height="260"
              src="https://cached.imagescaler.hbpl.co.uk/resize/scaleWidth/580/cached.offlinehbpl.hbpl.co.uk/news/NST/Twitter_Logo_WhiteOnBlue-20190122114927359.jpg"
              alt
            >
          </swiper-slide>

          <div class="swiper-pagination" slot="pagination"></div>
        </swiper>
      </md-card-media>
    </md-card>
  </div>
</template>

<script>
export default {
  name: "SectionFour",
  data() {
    return {
      swiperOption: {
        slidesPerView: 4,
        spaceBetween: 300,
        pagination: {
          el: ".swiper-pagination",
          clickable: true
        }
      }
    };
  }
};
</script>

<style scoped>
.headerTitle {
  padding: 10px 0 20px 0;
}
.headerTitle span {
  font-weight: 500;
}
hr {
  border-top: 2px solid #a6a6a6;
}
</style>


