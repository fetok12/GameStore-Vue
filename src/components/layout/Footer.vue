


  <template>
  <div>
    <footer class="mt-3">
      <div class="container">
        <div class="row">
          <div style="margin: 0 auto;">
            <ul>
              <li>
                <a href="#" class="text-white">Home</a>
              </li>
              <li>
                <a href="#" class="text-white">About</a>
              </li>
              <li>
                <a href="#" class="text-white">Contact</a>
              </li>
              <li>
                <a href="#" class="text-white">Privacy Policy</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
    <section id="feature">
      <div class="container">
        <div class="row">
          <div class="col-6 col-sm-3">
            <h5>About Us</h5>
            <ul>
              <li>Lorem ipsum dolor</li>
              <li>Sit Amet Consectetuer</li>
              <li>Adipiscing elit</li>
              <li>Sed diam nonummy nibh</li>
              <li>Euismod tincidunt</li>
              <li>Laoreet dolore magna</li>
              <li>Aliquam</li>
              <li>Erat</li>
            </ul>
          </div>
          <div class="col-6 col-sm-3">
            <h5>About Us</h5>
            <ul>
              <li>Lorem ipsum dolor</li>
              <li>Adipiscing elit</li>
              <li>Sed diam nonummy nibh</li>
              <li>Euismod tincidunt</li>
              <li>Laoreet dolore magna</li>
            </ul>
          </div>
          <div class="col-6 col-sm-3">
            <h5>About Us</h5>
            <ul>
              <li>Lorem ipsum dolor</li>
              <li>t lagna sed do</li>
              <li>Sed diam nonummy nibh</li>
              <li>Euismod tincidunt</li>
            </ul>
          </div>
          <div class="col-6 col-sm-3">
            <h5>About Us</h5>
            <ul>
              <li>Lorem ipsum dolor</li>
              <li>Sit Amet Consectetuer</li>
              <li>Adipiscing elit</li>
              <li>Sed diam nonummy nibh</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col text-center">ACME // right now</div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
section {
  padding: 40px 0 40px 0;
}

h5 {
  position: relative;
  right: 10px;
}
section#feature {
  background: #ff5000;
  color: white;
  padding: 40px;
  overflow: auto;
}
section#feature ul li {
  font-size: 14px;
  list-style: none;
  line-height: 2em;
}
footer {
  background: #333;
  color: #fff;
  padding: 30px 0 20px 0;
}

footer li {
  float: left;
  padding: 0 10px 0 10px;
  list-style: none;
}
footer a {
  text-decoration: none !important;
}
footer p {
  float: right;
}
</style>


