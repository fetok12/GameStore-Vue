<template>
  <div id="app">
    <Header/>
    <Navbar/>
    <Carousel/>
    <SectionOne/>
    <WhatsappSection/>
    <SectionTwo/>
    <SectionThree/>
    <SectionFour/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/layout/Header";
import Navbar from "./components/layout/Navbar";
import Carousel from "./components/layout/Carousel";
import SectionOne from "./components/layout/SectionOne";
import WhatsappSection from "./components/layout/WhatsappSection";
import SectionTwo from "./components/layout/SectionTwo";
import SectionThree from "./components/layout/SectionThree";
import SectionFour from "./components/layout/SectionFour";
import Footer from "./components/layout/Footer";
export default {
  name: "app",
  components: {
    Header,
    Navbar,
    Carousel,
    SectionOne,
    WhatsappSection,
    SectionTwo,
    SectionThree,
    SectionFour,
    Footer
  }
};
</script>


<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}

.btn {
  display: inline-block;
  border: none;
  background: #555;
  color: #fff;
  padding: 7px 20px;
  cursor: pointer;
}

.btn:hover {
  background: #666;
}
</style>
