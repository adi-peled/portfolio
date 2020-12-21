<template>
  <footer class="footer" id="contact ">
    <div class="contact">
      <h3 class="footer__title">Contact me</h3>
      <a
        class="footer__link"
        target="_blank"
        href="https://mail.google.com/mail/?view=cm&fs=1&to=adipeled499@gmail.com&su=&body=text here "
      >
        <EmailSvg style="{style.svgFirst}" className="svg"></EmailSvg>
        <label style="{style.labelFirst}">
          Email Me: adipeled499@gmail.com</label
        >
      </a>

      <a
        class="footer__link"
        target="_blank"
        href="https://api.whatsapp.com/send?phone=972556699584"
      >
        <WhatsappSvg style="{style.svgSecond}" className="svg"></WhatsappSvg>

        <label style="{style.labelSecond}">
          Send Whatsapp: 055-6699584</label
        ></a
      >
    </div>
    <p class="footer__copyright">
      Built by Adi Peled Copyright &copy; by jonas Schmedtmann
    </p>
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

