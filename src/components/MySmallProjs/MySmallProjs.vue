<template>
  <section class="my-small-projs">
      <div class="center-text mar-btm-medium">
    <h3 class="heading-secondary">My small Projects</h3>
      </div>
    <div class="projs-list flex wrap" v-if="projects">
      <ProjectPreview
        v-for="project in projects"
        :project="project"
        :key="project.id"
      />
    </div>
  </section>
</template>

<script>
import "./MySmallProjs.scss";
import ProjectPreview from "../ProjectPreview/ProjectPreview";
import projectService from "../../services/projects";
export default {
  name: "MySmallProjs",
  data() {
    return {
      projects: [],
    };
  },
  created() {
    this.projects = projectService.getProjects();
    console.log(this.projects);
  },
  components: {
    ProjectPreview,
  },
};
</script>
