<script>
export default {
  name: "Footer"
}
</script>

<template>
  <footer>

    <div class="container">

      <div class="contact-box wow rotateIn animated" data-wow-offset="10" data-wow-duration="1s">

        <!-- CONTACT BUTTON TO EXPAND OR COLLAPSE FORM -->

        <a class="btn contact-button expand-form expanded"><i class="far fa-envelope-open" aria-hidden="true"></i></a>

        <!-- EXPANDED CONTACT FORM -->
        <div class="row expanded-contact-form">

          <div class="col-sm-8 col-sm-offset-2">

            <!-- FORM -->
            <form class="contact-form" id="contact" role="form">

              <!-- IF MAIL SENT SUCCESSFULLY -->
              <h4 class="success">
                <i class="icon_check"></i> Ваше сообщение успешно отправлено!
              </h4>

              <!-- IF MAIL SENDING UNSUCCESSFULL -->
              <h4 class="error">
                <i class="icon_error-circle_alt"></i> E-mail недействительный и сообщение должно быть больше
                1 символа
              </h4>

              <div class="col-sm-6">
                <input class="form-control input-box" id="name" type="text" name="name"
                       placeholder="Ваше имя">
              </div>

              <div class="col-sm-6">
                <input class="form-control input-box" id="email" type="email" name="email"
                       placeholder="Ваш Email">
              </div>

              <div class="col-sm-12">
                <input class="form-control input-box" id="subject" type="text" name="subject"
                       placeholder="+375291111111">
                <textarea class="form-control textarea-box" id="message" rows="8"
                          placeholder="Сообщение"></textarea>
              </div>

              <button class="btn btn-primary standard-button2 ladda-button" type="submit" id="submit"
                      name="submit" data-style="expand-left">Отправить
              </button>

            </form>
            <!-- /END FORM -->

          </div>

        </div>
        <!-- /END EXPANDED CONTACT FORM -->

      </div>
      <!-- /END CONTACT BOX -->


      <!-- SOCIAL ICONS -->
      <ul class="social-icons">
        <li><a href="https://www.facebook.com/gena.nikan" target="_blank">
          <i class="fab fa-facebook-square" aria-hidden="true"></i></a></li>
        <li><a href="https://www.youtube.com/watch?v=gLA3Hgn-1Po" target="_blank">
          <i class="fab fa-youtube" aria-hidden="true"></i></a></li>
        <li><a href="https://www.instagram.com/gena_nikanchik/" target="_blank">
          <i class="fab fa-instagram" aria-hidden="true"></i></a></li>
        <li><a href="https://vk.com/barman_show_nikanchyk" target="_blank">
          <i class="fab fa-vk" aria-hidden="true"></i></a></li>
        <li><a href="viber://chat?number=375293846785">
          <i class="fab fa-viber" aria-hidden="true"></i></a></li>
      </ul>

      <!-- COPYRIGHT TEXT -->
      <p class="copyright">
        ©2017-2020 Glebov Anton, All Rights Reserved
      </p>

    </div>
    <!-- /END CONTAINER -->

  </footer>
</template>

<style scoped>

</style>