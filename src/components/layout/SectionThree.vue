<template>
  <div class="container">
    <div class="headerTitle">
      <i class="fab fa-gg-circle"></i>
      <span class="ml-2">News</span>
      <hr>
      <div class="row">
        <div class="col-6 col-sm-6 col-md-3" v-bind:key="user.id" v-for="user in users">
          <b-card
            img-src="https://nexus.leagueoflegends.com/wp-content/uploads/2019/06/Banner_T2_Image_tnp3w61gzna8r2n3rojp.jpg"
            img-alt="Image"
            img-top
            style="max-width: 20rem; background-color:#f7f6f5; border:none; height:270px; "
            class="mb-2"
          >
            <b-card-text class="title">{{user.company.catchPhrase}}</b-card-text>

            <div style="float:right; position:absolute; right:10px; bottom:10px">
              <div class="oldPrice">
                <div id="lineThroughPrice">35.45 Ł</div>
                <div id="newPrice">25.50 Ł</div>
              </div>
              <div class="cardPrice">
                <p>{{user.id}}</p>
              </div>
            </div>
          </b-card>
        </div>
      </div>
    </div>
  </div>
</template>



<script>
import axios from "axios";
export default {
  name: "SectionThree",
  methods: {},
  data() {
    return {
      users: []
    };
  },
  created() {
    axios
      .get("https://jsonplaceholder.typicode.com/users?_limit=8")
      .then(res => (this.users = res.data))
      .catch(() => {
        //console.log(err)
      });
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


