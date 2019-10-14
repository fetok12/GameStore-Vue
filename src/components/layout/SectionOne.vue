<template>
  <div class="container sectionOne">
    <div class="row">
      <div class="col-6 col-sm-6 col-md-6 col-lg-3">
        <b-card
          img-src="https://nexus.leagueoflegends.com/wp-content/uploads/2019/06/Banner_T2_Image_tnp3w61gzna8r2n3rojp.jpg"
          img-alt="Image"
          img-top
          img-height="140"
          style="max-width: 20rem; background-color:#f7f6f5; border:none"
          class="mb-2"
        >
          <b-card-text class="title">League of Legends: Riot Point</b-card-text>

          <div style="float:right">
            <div class="oldPrice">
              <div id="lineThroughPrice">35.45 Ł</div>
              <div id="newPrice">25.50 Ł</div>
            </div>
            <div class="cardPrice">
              <p>-15%</p>
            </div>
          </div>
        </b-card>
      </div>
      <div class="col-6 col-sm-6 col-md-6 col-lg-3">
        <b-card
          img-src="https://www.extremetech.com/wp-content/uploads/2017/12/PUBG-Feature-640x353.jpg"
          img-alt="Image"
          img-top
          img-height="140"
          style="max-width: 20rem; background-color:#f7f6f5; border:none"
          class="mb-2"
        >
          <b-card-text class="title">League of Legends: Riot Point</b-card-text>

          <div style="float:right">
            <div class="oldPrice">
              <div id="lineThroughPrice">35.45 Ł</div>
              <div id="newPrice">25.50 Ł</div>
            </div>
            <div class="cardPrice">
              <p>-15%</p>
            </div>
          </div>
        </b-card>
      </div>
      <div class="col-6 col-sm-6 col-md-6 col-lg-3">
        <b-card
          img-src="https://steamcdn-a.akamaihd.net/steam/apps/870780/header.jpg?t=1566940851"
          img-alt="Image"
          img-top
          img-height="140"
          style="max-width: 20rem; background-color:#f7f6f5; border:none"
          class="mb-2"
        >
          <b-card-text class="title">League of Legends: Riot Point</b-card-text>

          <div style="float:right">
            <div class="oldPrice">
              <div id="lineThroughPrice">35.45 Ł</div>
              <div id="newPrice">25.50 Ł</div>
            </div>
            <div class="cardPrice">
              <p>-15%</p>
            </div>
          </div>
        </b-card>
      </div>
      <div class="col-6 col-sm-6 col-md-6 col-lg-3">
        <b-card
          img-src="https://cdn02.nintendo-europe.com/media/images/10_share_images/games_15/nintendo_switch_4/H2x1_NSwitch_EASportsFifa19_image1600w.jpg"
          img-alt="Image"
          img-top
          img-height="140"
          style="max-width: 20rem; background-color:#f7f6f5; border:none"
          class="mb-2"
        >
          <b-card-text class="title">League of Legends: Riot Point</b-card-text>

          <div style="float:right">
            <div class="oldPrice">
              <div id="lineThroughPrice">35.45 Ł</div>
              <div id="newPrice">25.50 Ł</div>
            </div>
            <div class="cardPrice">
              <p>-15%</p>
            </div>
          </div>
        </b-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.sectionOne {
  margin-top: 10px;
}
.title {
  font-weight: 600;
  font-size: 14px;
}
#new {
  width: 50px;
  height: 30px;
  background-color: #d71920;
  float: left;
  border-radius: 1px;
  display: block;
}
.cardPrice {
  width: 50px;
  height: 30px;
  background-color: #d71920;
  float: right;
  border-radius: 1px;
  margin-top: 11px;
}
#lineThroughPrice {
  text-decoration: line-through;
  font-size: 12px;
  color: grey;
}

#newPrice {
  font-weight: 500;
}
.oldPrice {
  float: right;
  margin-left: 1em;
}

.cardPrice p {
  text-align: center;
  color: aliceblue;
  padding: 0;
  margin-top: 2px;
}
</style>


