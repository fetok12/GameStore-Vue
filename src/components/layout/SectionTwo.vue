<template>
  <div class="container">
    <div class="headerTitle">
      <i class="fab fa-gg-circle"></i>
      <span class="ml-2">Separate 2</span>
      <hr>
    </div>
    <div class="row">
      <div class="col-12 col-sm-12 col-md-12 col-lg-6">
        <b-card
          img-src="https://nexus.leagueoflegends.com/wp-content/uploads/2019/06/Banner_T2_Image_tnp3w61gzna8r2n3rojp.jpg"
          img-alt="Image"
          img-top
          style="max-width: 50rem; background-color:#f7f6f5; border:none"
          class="mb-2"
        >
          <b-card-text class="title">League of Legends: Riot Point</b-card-text>

          <div style="float:left">
            <div id="bonus">+ BONUS</div>
          </div>

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
      <div class="col-12 col-sm-12 col-md-12 col-lg-6">
        <div class="row">
          <div class="col-6 col-sm-6 col-md-6">
            <b-card
              img-src="https://hb.imgix.net/4817793a4611f48dae98d819c0940f0047956291.jpg?auto=compress,format&fit=crop&h=353&w=616&s=723c6d4386846dc6dfc5fba499e34ca0"
              img-alt="Image"
              img-top
              img-height="140"
              style="max-width: 40rem; background-color:#f7f6f5; border:none"
              class="mb-2"
            >
              <div>
                <b-card-text class="title2">League of Legends: Riot Point</b-card-text>
              </div>

              <div style="float:left">
                <div id="bonus2">+ BONUS</div>
              </div>

              <div style="float:right">
                <div class="oldPrice2">
                  <div id="lineThroughPrice2">35.45 Ł</div>
                  <div id="newPrice2">25.50 Ł</div>
                </div>
                <div class="cardPrice2">
                  <p>-15%</p>
                </div>
              </div>
            </b-card>
          </div>
          <div class="col-6 col-sm-6 col-md-6">
            <b-card
              img-src="https://www.extremetech.com/wp-content/uploads/2017/12/PUBG-Feature-640x353.jpg"
              img-alt="Image"
              img-top
              img-height="140"
              style="max-width: 40rem; background-color:#f7f6f5; border:none"
              class="mb-2"
            >
              <div>
                <b-card-text class="title2">League of Legends: Riot Point</b-card-text>
              </div>

              <div style="float:left">
                <div id="bonus2">+ BONUS</div>
              </div>

              <div style="float:right">
                <div class="oldPrice2">
                  <div id="lineThroughPrice2">35.45 Ł</div>
                  <div id="newPrice2">25.50 Ł</div>
                </div>
                <div class="cardPrice2">
                  <p>-15%</p>
                </div>
              </div>
            </b-card>
          </div>
          <div class="col-6 col-sm-6 col-md-6">
            <b-card
              img-src="https://nexus.leagueoflegends.com/wp-content/uploads/2019/06/Banner_T2_Image_tnp3w61gzna8r2n3rojp.jpg"
              img-alt="Image"
              img-top
              img-height="140"
              style="max-width: 40rem; background-color:#f7f6f5; border:none"
              class="mb-2"
            >
              <div>
                <b-card-text class="title2">League of Legends: Riot Point</b-card-text>
              </div>

              <div style="float:left">
                <div id="bonus2">+ BONUS</div>
              </div>

              <div style="float:right">
                <div class="oldPrice2">
                  <div id="lineThroughPrice2">35.45 Ł</div>
                  <div id="newPrice2">25.50 Ł</div>
                </div>
                <div class="cardPrice2">
                  <p>-15%</p>
                </div>
              </div>
            </b-card>
          </div>
          <div class="col-6 col-sm-6 col-md-6">
            <b-card
              img-src="https://nexus.leagueoflegends.com/wp-content/uploads/2019/06/Banner_T2_Image_tnp3w61gzna8r2n3rojp.jpg"
              img-alt="Image"
              img-top
              img-height="140"
              style="max-width: 40rem; background-color:#f7f6f5; border:none"
              class="mb-2"
            >
              <div>
                <b-card-text class="title2">League of Legends: Riot Point</b-card-text>
              </div>

              <div style="float:left">
                <div id="bonus2">+ BONUS</div>
              </div>

              <div style="float:right">
                <div class="oldPrice2">
                  <div id="lineThroughPrice2">35.45 Ł</div>
                  <div id="newPrice2">25.50 Ł</div>
                </div>
                <div class="cardPrice2">
                  <p>-15%</p>
                </div>
              </div>
            </b-card>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionTwo"
};
</script>

<style scoped>
.title {
  padding: 10px 0 50px 0;
}
.headerTitle {
  padding: 10px 0 20px 0;
}
.headerTitle span {
  font-weight: 500;
}
hr {
  border-top: 2px solid #a6a6a6;
}
.title {
  font-weight: 600;
  font-size: 19px;
}
.cardPrice {
  padding: 5px 15px 10px 15px;
  background-color: #d71920;
  float: right;
  border-radius: 3px;
  margin-top: 10px;
}
#lineThroughPrice {
  text-decoration: line-through;
  font-size: 14px;
  color: grey;
}

#newPrice {
  font-weight: 500;
  font-size: 24px;
}
.oldPrice {
  float: right;
  margin-left: 1em;
}

.cardPrice p {
  font-size: 20px;
  text-align: center;
  color: aliceblue;
  padding: 0;
  margin: 0;
}
#bonus {
  padding: 5px 15px 10px 15px;
  background-color: #423e3f;
  border-radius: 3px;
  margin-top: 10px;
  color: white;
  font-size: 19px;
  font-weight: 500;
}

.title2 {
  font-weight: 600;
  font-size: 14px;
}

.cardPrice2 {
  width: 50px;
  height: 30px;
  background-color: #d71920;
  float: right;
  border-radius: 1px;
  margin-top: 11px;
}
#lineThroughPrice2 {
  text-decoration: line-through;
  font-size: 12px;
  color: grey;
}
#bonus2 {
  padding: 5px 10px 10px 10px;
  background-color: #423e3f;
  border-radius: 3px;
  margin-top: 10px;
  color: white;
  font-size: 12px;
  font-weight: 500;
}

#newPrice2 {
  font-weight: 500;
}
.oldPrice2 {
  float: right;
  margin-left: 1em;
}

.cardPrice2 p {
  text-align: center;
  color: aliceblue;
  padding: 0;
  margin-top: 2px;
}
</style>


