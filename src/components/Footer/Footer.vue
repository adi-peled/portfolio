<template>
  <footer class="footer" id="contact ">
    <p class="footer__copyright">Built by Adi Peled  Copyright &copy; by jonas Schmedtmann   </p>
    <ul class="flex">
      <li>
        <Facebook class="svg" />
      </li>
      <li>
        <Instagram class="svg" />
      </li>
      <li>
        <Linkedin class="svg" />
      </li>
    </ul>
  </footer>
</template>

<script>
import "./Footer.scss";
// import Facebook from "../../assets/img/social/facebook.svg";
import Facebook from "@/assets/img/social/facebook.svg";
import Instagram from "@/assets/img/social/instagram.svg";
import Linkedin from "@/assets/img/social/linkedin.svg";

export default {
  name: "Footer",
  components: {
    Facebook,
    Instagram,
    Linkedin,
  },
};
</script>

