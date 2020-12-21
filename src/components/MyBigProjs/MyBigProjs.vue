<template>
  <section class="projects-list" id="projects">
    <div class="center-text mar-btm-big">
      <h3 class="heading-secondary">My biggest projects</h3>
    </div>

    <div class="flex space-around">
      <div class="project">
        <div class="project__front project__front--2 project__side">
          <div class="project__img project__img--2"></div>
          <h4 class="project__heading project__heading--2">Rcrentals</h4>
          <div class="project__desc">
            <h5>
              Marketplace for car rentals, diffrent users can upload their cars
              around the world
            </h5>
            <ul class="project__list">
              <li class="project__item">Vue.js & vueX</li>
              <li class="project__item">Node.js</li>
              <li class="project__item">MongoDB</li>
              <li class="project__item">Sockets</li>
            </ul>
          </div>
        </div>

        <div class="project__back project__back--2 project__side">
          <a href="https://rcrentals.herokuapp.com" class="btn" target="_blank">
            go to Rcrentals
          </a>
        </div>
      </div>
      <div class="project">
        <div class="project__front project__front--1 project__side">
          <div class="project__img project__img--1"></div>
          <h4 class="project__heading project__heading--1">slack clone</h4>
          <div class="project__desc">
            <h5>Chat app, diffrent and varied channels</h5>
            <ul class="project__list">
              <li class="project__item">React JS</li>
              <li class="project__item">Real-time database (Firebase)</li>
              <li class="project__item">React Context API</li>
              <li class="project__item">React router</li>
              <li class="project__item">Material UI</li>
            </ul>
          </div>
        </div>

        <div class="project__back project__back--1 project__side">
          <a
            href="https://slack-clone-dc435.web.app"
            class="btn"
            target="_blank"
          >
            go to slack clone
          </a>
        </div>
      </div>
      <div class="project">
        <div class="project__front project__front--3 project__side">
          <div class="project__img project__img--3"></div>
          <h4 class="project__heading project__heading--3">clothing store</h4>
          <div class="project__desc">
            <h5>
              Looking for new clothes? this is your app. various of new clothes
              in one shop
            </h5>
            <ul class="project__list">
              <li class="project__item">React & Redux</li>
              <li class="project__item">Node.js</li>
              <li class="project__item">MongoDB</li>
              <li class="project__item">Nodemailer</li>
            </ul>
          </div>
        </div>

        <div class="project__back project__back--3 project__side">
          <a
            href="https://adi-clothing-store.herokuapp.com/"
            class="btn"
            target="_blank"
          >
            go to clothing store
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import "./MyBigProjs.scss";
// import BigProjectPreview from "../BigProjPreview/BigProjPreview";
export default {
  name: "MyBigProjs",
  data() {
    return {
      projects: [],
    };
  },
  created() {},
  components: {
    // BigProjectPreview,
  },
};
</script>
