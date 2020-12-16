<template>
  <div id="app">
    <div class="app-header">
    <Header />
    <Hero/>
    </div>
    <main class="app-container">
      <MyBigProjs />
      <MySmallProjs/>
      <Profile />
    </main>
    <Footer />
  </div>
</template>

<script>
import './app.scss'
import Footer from "./components/Footer/Footer";
import Header from "./components/Header/Header";
import MyBigProjs from "./components/MyBigProjs/MyBigProjs";
import MySmallProjs from "./components/MySmallProjs/MySmallProjs";
import Profile from "./components/Profile/Profile";
import Hero from "./components/Hero/Hero";
export default {
  name: "app",
  components: {
    Header,
    Footer,
    MyBigProjs,
    Profile,
    Hero,
    MySmallProjs
  },
};
</script>

