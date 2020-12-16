<template>
  <section class="project-preview flex">
    <h4 class="heading-tertiary ">{{ project.title }}</h4>
    <p class="desc">{{ project.desc }}</p>
    <img :src="require(`@/assets/img/projs/${project.title}.png`)" />
      <a class="btn"
        v-if="project.type === 'github'"
        :href="`https://adi-peled.github.io/${project.title}/`"
        target="_blank"
      >
        go to <span>{{ project.title }}</span></a
      >
      <a class="btn"
        v-else-if="project.type === 'heroku'"
        :href="`https://${project.title}.herokuapp.com/#/`"
        target="_blank"
      >
        go to <span>{{ project.title }}</span></a
      >
      <a class="btn"
        v-else
        :href="`https://${project.title}-dc435.web.app/`"
        target="_blank"
      >
        go to <span>{{ project.title }}</span></a
      >
  </section>
</template>

<script>
import "./ProjectPreview.scss";
export default {
  name: "ProjectPreview",
  props: ["project"],
  data() {
    return {};
  },
};
</script>
