<template>
  <section id="profile" class="profile ">
    <div class="profile__container flex">
      <div class="profile__left flex">
        <img src="@/assets/img/profile.jpeg" />
        <h3 class="profile__name">Adi Peled</h3>
        <h4 class="profile__subtitle">Full Stack Web Developer</h4>
      </div>

      <div class="profile__right flex">
        <div class="desc flex">
          <h3 class="heading-secondary">Summary</h3>
          <p class="desc__summary">
            Full Stack / Frontend Web Developer experienced with building
            single-page applications using advanced technologies such as
            Node.js, Vue.js, React and Angular. Graduate of Coding Academy
            bootcamp.
          </p>
          <div class="desc__skills">
            <h3 class="heading-secondary">Skills</h3>
            <ul>
              <li>Frameworks: Vue.js & Vuex, React & Redux, Angular</li>
              <li>
                JaveScript, ES6, TypeScript, HTML5, CSS3, SASS, jQuery, Bootsrap
              </li>
              <li>Node.js, REST API, Firebase, MongoDB, SQL.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import "./Profile.scss";
export default {
  name: "Profile",
};
</script>
