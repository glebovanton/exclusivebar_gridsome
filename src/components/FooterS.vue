<script>
export default {
  name: "FooterS",
};
</script>

<template>
  <footer>
    <div class="container">
      <!-- SOCIAL ICONS -->
      <ul class="social-icons">
        <li>
          <a href="https://www.facebook.com/gena.nikan" target="_blank">
            <font-awesome class="icon" :icon="['fab', 'facebook-square']"
          /></a>
        </li>
        <li>
          <a href="https://www.youtube.com/watch?v=gLA3Hgn-1Po" target="_blank">
            <font-awesome class="icon" :icon="['fab', 'youtube']"
          /></a>
        </li>
        <li>
          <a href="https://www.instagram.com/gena_nikanchik/" target="_blank">
            <font-awesome class="icon" :icon="['fab', 'instagram']"
          /></a>
        </li>
        <li>
          <a href="https://vk.com/barman_show_nikanchyk" target="_blank">
            <font-awesome class="icon" :icon="['fab', 'vk']"
          /></a>
        </li>
        <li>
          <a href="viber://chat?number=375293846785">
            <font-awesome class="icon" :icon="['fab', 'viber']"
          /></a>
        </li>
      </ul>

      <!-- COPYRIGHT TEXT -->
      <p class="copyright">©2017-2020 Glebov Anton, All Rights Reserved</p>
    </div>
    <!-- /END CONTAINER -->
  </footer>
</template>

<style lang="scss" scoped>
footer .contact-button,
.features .feature .icon-container .icon {
  border: 1px solid #b5894a !important;
  color: #b5894a !important;
}

footer .contact-box {
  margin-bottom: 78px;
}

footer .contact-box .contact-button {
  height: 80px;
  width: 80px;
  border-radius: 50%;
  margin: auto;
  position: relative;
  font-size: 30px;
  line-height: 60px;
  vertical-align: middle;
  margin-top: -40px;
  background: #232323;
  -webkit-box-shadow: 0 0 0 3px #232323;
  box-shadow: 0 0 0 3px #232323;
  -webkit-backface-visibility: hidden;
  -webkit-background-clip: padding-box;
  -moz-background-clip: padding;
  background-clip: padding-box;
}

footer .contact-box .contact-button:hover {
  color: #ffffff;
}

footer .contact-box .expanded-contact-form {
  margin-top: 40px;
  display: none;
}

footer .contact-box .expanded-contact-form .success,
footer .contact-box .expanded-contact-form .error {
  display: none;
}

footer .contact-box .expanded-contact-form .input-box {
  margin-bottom: 10px;
  margin-top: 10px;
  height: 50px;
  -webkit-box-shadow: none;
  box-shadow: none;
  background: #222222;
  border: 1px solid #161616;
}

footer .contact-box .expanded-contact-form .textarea-box {
  margin-top: 20px;
  margin-bottom: 20px;
  -webkit-box-shadow: none;
  box-shadow: none;
  background: #222222;
  border: 1px solid #161616;
}

footer .contact-box .expanded-contact-form .textarea-box:active,
footer .contact-box .expanded-contact-form .textarea-box:focus {
  color: #fff;
}

footer .social-icons {
  margin-top: 30px;
  border-bottom: 1px solid #111111;
  padding-bottom: 50px;
}

footer .social-icons li {
  display: inline-block;
  margin: 5px;
}

footer .social-icons li a {
  font-size: 30px;
  color: #636363;
}

footer .social-icons li a:hover {
  color: #b5894a;
}

footer .copyright {
  color: #808080;
  padding-top: 10px;
  margin-bottom: 50px;
}
</style>
