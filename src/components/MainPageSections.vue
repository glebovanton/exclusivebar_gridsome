<script>
export default {
  name: "MainPageSections"
}
</script>

<template>
  <div class="sections-wrapper">
  <!-- =========================
       FEATURES
  ============================== -->
  <section class="features deep-dark-bg" id="features">

    <div class="container">

      <!-- SECTION HEADER -->
      <div class="section-header wow fadeIn animated" data-wow-offset="120" data-wow-duration="1.5s">

        <!-- SECTION TITLE -->
        <div class="colored-line">
        </div>
        <h2 class="white-text">Exclusive Bar Catering</h2>
        <div class="colored-line">
        </div>

      </div>
      <!-- /END SECTION HEADER -->


      <div class="row">

        <!-- FEATURES LEFT -->
        <div class="col-xs-5 col-md-5 features-left wow fadeInLeft animated" data-wow-offset="10"
             data-wow-duration="1.5s">

          <!-- FEATURE BAR -->
          <div class="feature">

            <!-- ICON -->
            <div class="icon-container">
              <div class="icon">
                <i class="fas fa-map-marker-alt"></i>
              </div>
            </div>

            <!-- FEATURE HEADING AND DESCRIPTION -->
            <div class="fetaure-details">
              <h4><a class="main-color " href="#brief0" target="_blank">Выездной коктейль бар</a></h4>
              <p>
                Выездной Коктейль Бар создан удивить ваших гостей вкуснейшими напитками и создать уютную
                атмосферу праздника.<br>
                <a href="examples.html" target="_blank"> <span
                    style="color: #b5894a; font-size: 80%; font-stretch: normal">Примеры работ</span></a>
                <br>
              </p>
              <!--<span style=""></span>-->

            </div>

          </div>
          <!-- /END SINGLE FEATURE BAR -->

          <!-- FEATURE AI-->
          <div class="feature">

            <!-- ICON -->
            <div class="icon-container">
              <div class="icon">
                <i class="fas fa-trophy" aria-hidden="true"></i>
              </div>
            </div>

            <!-- FEATURE HEADING AND DESCRIPTION -->
            <div class="fetaure-details">
              <h4><a class="main-color " href="#brief1">Бармен шоу</a></h4>
              <p>
                Бармен шоу-это по настоящему высший профессионализм барного искусства, который несет
                зрелищность и оригинальность. <br>
                <a href="barmenshow.html" target="_blank"> <span
                    style="color: #b5894a; font-size: 80%; font-stretch: normal">Подробнее </span></a>
              </p>
            </div>

          </div>
          <!-- /END SINGLE FEATURE AI-->


        </div>
        <!-- /END FEATURES LEFT -->

        <!--SHACKERS IMAGE-->
        <div class="col-xs-2 col-md-2 hidden-xs">
          <!--                <div class="phone-image wow bounceIn animated" data-wow-offset="120" data-wow-duration="1.5s">
                              <img src="images/barman4.png" alt="">
                          </div>-->
        </div>

        <!-- FEATURES RIGHT -->
        <div class="col-xs-5 col-md-5 features-right wow fadeInRight animated" data-wow-offset="10"
             data-wow-duration="1.5s">

          <!-- FEATURE MAP -->
          <div class="feature">

            <!-- ICON -->
            <div class="icon-container">
              <div class="icon">
                <i class="fas fa-glass-martini" aria-hidden="true"></i>
              </div>
            </div>

            <!-- FEATURE HEADING AND DESCRIPTION -->
            <div class="fetaure-details">
              <h4><a class="main-color " href="#brief2">Пирамида из бокалов</a></h4>
              <p>
                Пирамида из бокалов поможет раскрепостить гостей, наладить общение и разбавить атмосферу
                праздника.
                <br>
                <a href="examples.html#examples-pyramids_list" target="_blank"> <span
                    style="color: #b5894a; font-size: 80%; font-stretch: normal">Наши работы </span></a>
              </p>
            </div>

          </div>
          <!-- /END SINGLE FEATURE MAP -->

          <!-- FEATURE GEO-->
          <div class="feature">

            <!-- ICON -->
            <div class="icon-container">
              <div class="icon">
                <i class="far fa-money-bill-alt" aria-hidden="true"></i>
              </div>
            </div>

            <!-- FEATURE HEADING AND DESCRIPTION -->
            <div class="fetaure-details">
              <h4><a class="main-color " href="#brief3">Аренда оборудования</a></h4>
              <p>
                Аренда профессионального оборудования для различного типа мероприятий.
              </p>
            </div>

          </div>
          <!-- /END SINGLE FEATURE GEO-->
        </div>
        <!-- /END FEATURES RIGHT -->


      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END FEATURES SECTION -->

  <!-- =========================
       BRIEF RIGHT SECTION 0
  ============================== -->
  <section class="app-brief " id="brief0">

    <div class="container">

      <div class="row">

        <!-- BRIEF -->
        <div class="col-sm-6 left-align wow fadeInLeft animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SECTION TITLE -->
          <h1 class="white-text">Выездной коктейль бар</h1>

          <div class="colored-line-left">
          </div>

          <p><span>«Exclusive Bar Catering»</span> представляет актуальное на сегодняшний день направление
            выездной коктейль бар. Данная услуга подразумевает собой организацию и работу полноценного бара в
            любом месте и назначенное время вашего мероприятия.</p>
          <g-link target="_blank" to="/cocktails/" class="link-reset" style="color: #b5894a; font-size: 130%;">Перейти к коктейльной карте</g-link>
          <h3>Мы предлагаем выбор:</h3>
          <ul class="feature-list">
            <li><i class="far fa-check-square"></i> Барные зоны выполненные в различных
              стилях, которые будут идеально гармонировать со стилистикой вашего мероприятия.
            </li>
            <li><i class="far fa-check-square"></i> Авторская коктейльная карта с
              оригинальной подачей в элитной посуде.
            </li>
            <li><i class="far fa-check-square"></i> Работа бара «под ключ»(«Все включено»)
              или вариант работы с вашей продукцией.
            </li>
            <li><i class="far fa-check-square"></i> Проведение мастер-классов, дегустаций от
              профессиональных
              Барменов. Интерактивный мастер-класс с приготовлением коктейлей от гостей.
            </li>

          </ul>
          <p>Каждый гость на вашем мероприятии индивидуален , а наша команда профессиональных барменов найдет
            подход к каждому из них, приветливо и внимательно выполнит пожелания.
          </p>


        </div>
        <!-- /ENDBRIEF -->

        <!-- PHONES IMAGE -->
        <div class="col-sm-6 wow fadeInRight animated" data-wow-offset="10" data-wow-duration="1.5s">
          <div class="phone-image">
            <img src="images/geo3.png" alt="" эксклюзивбар>
          </div>
        </div>
        <!-- /END PHONES IMAGE -->

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SECTION 0-->
  <!-- =========================
       BRIEF LEFT SECTION 1
  ============================== -->
  <section class="app-brief deep-dark-bg" id="brief1">


    <div class="container">

      <div class="row">

        <!-- PHONES IMAGE -->
        <div class="col-sm-6 wow fadeInRight animated" data-wow-offset="10" data-wow-duration="1.5s">
          <div class="phone-image">
            <img src="images/barman4.png" alt="эксклюзив бар">
          </div>
        </div>
        <!-- /END PHONES IMAGE -->

        <!-- BRIEF -->
        <div class="col-sm-6 left-align wow fadeInLeft animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SECTION TITLE -->
          <h1 class="white-text">Бармен шоу</h1>

          <div class="colored-line-left">
          </div>

          <p>
            Бармен шоу-это по настоящему высший профессионализм барного искусства, который несет зрелищность и
            оригинальность.
            Перед шоу-барменом стоит задача не просто красиво жонглировать бутылками и демонстрировать различные
            элементы флейринга, а окунуть зрителя в динамичное представление, полностью гармонирующее с музыкой
            и при этом уделить должное внимание приготовлению смешанных напитков.
            От «Exclusive Bar Catering» выступает чемпион Беларуси по флейрингу Геннадий Никанчик.
            Техника выступления отрабатывается долгими и упорными тренировками.
          </p>
          <!--<a href="#brief4"> <span style="color: #b5894a; font-size: 110%; font-stretch: normal" >«Смотреть видео» </span></a>-->
          <!--<a href="#brief4" class="btn btn-default standard-button"> Смотреть видео </a>-->
          <a href="barmenshow.html" target="_blank" class="b-ff-index-intro__btn-down"></a>

        </div>
        <!-- /ENDBRIEF -->

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SECTION 1 -->


  <!-- =========================
       BRIEF RIGHT SECTION 2
  ============================== -->
  <section class="app-brief" id="brief2">

    <div class="container">

      <div class="row">


        <!-- RIGHT SIDE WITH BRIEF -->
        <div class="col-sm-6 left-align wow fadeInLeft animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SECTION TITLE -->
          <h1 class="white-text">Пирамида из бокалов</h1>

          <div class="colored-line-left">
          </div>

          <p>
            Сегодня уже мало кого можно удивить пирамидой из бокалов, но сделав ее необычной, из элитных бокалов
            и со вкусом, она станет не только украшением торжества, но и ее изюминкой.
            В стилистику вашего мероприятия можно подобрать стол, бокалы, напитки, гарниры, спец. эффекты ..
            Пирамида из бокалов поможет раскрепостить гостей, наладить общение и разбавить атмосферу праздника.

          </p>

          <!-- FEATURE LIST -->
          <ul class="feature-list">
            <li><i class="far fa-thumbs-up"></i> Оптимальный вариант</li>
            <li><i class="far fa-money-bill-alt"></i> Выгодное предложение</li>
            <li><i class="fas fa-users"></i>Корпоративное решение</li>
          </ul>

        </div>
        <!-- /END RIGHT BRIEF -->

        <!-- PHONES IMAGE -->
        <div class="col-sm-6 wow fadeInRight animated" data-wow-offset="10" data-wow-duration="1.5s">
          <div class="phone-image">
            <img src="images/pyramid3.png" alt="Пирамида из бокалов">
          </div>
        </div>

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SECTION 2-->


  <!-- =========================
       BRIEF LEFT SECTION 3
  ============================== -->
  <section class="app-brief deep-dark-bg" id="brief3">

    <div class="container">

      <div class="row">

        <!-- PHONES IMAGE -->
        <div class="col-sm-6 wow fadeInRight animated" data-wow-offset="10" data-wow-duration="1.5s">
          <div class="phone-image">
            <img src="images/rent3.png" alt="Аренда оборудования">
          </div>
        </div>

        <!-- RIGHT SIDE WITH BRIEF -->
        <div class="col-sm-6 left-align wow fadeInLeft animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SECTION TITLE -->
          <h1 class="white-text">Аренда оборудования</h1>

          <div class="colored-line-left">
          </div>

          <p>
            Аренда профессионального оборудования для различного типа мероприятий.

          </p>

          <!-- FEATURE LIST -->
          <ul class="feature-list">
            <li><i class="far fa-check-square"></i> Барные стойки.Выставочная или барная
              зона, диджейский пульт или рецепшн на ваш выбор.
            </li>
            <li><i class="far fa-check-square"></i> Аренда бокалов. Вы можете выбрать не
              только бокалы для коктейлей но и бокалы для сервировки стола вашего главного дня.
            </li>
            <li><i class="far fa-check-square"></i> Термоконтейнеры. Простой способ перевозки
              и хранения льда.
            </li>
            <li><i class="far fa-check-square"></i> Оборудование и инвентарь для работы бара.
            </li>
          </ul>

        </div>
        <!-- /END RIGHT BRIEF -->

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SECTION 3 -->

  <!-- =========================
       BRIEF RIGHT  SECTION  4 VIDEO
  ============================== -->
  <section class="app-brief" id="brief4">

    <div class="container-fluid">

      <div class="row">
        <!-- video brief -->
        <div class="col-xs-12">
          <div class="video-container">

            <div class="video">

              <!--<iframe width="640" height="360" src="https://www.youtube.com/embed/D0Yfs1llkTc?rel=0"
                      frameborder="0" allowfullscreen></iframe>-->
              <iframe id="video" src="https://player.vimeo.com/video/243995432" width="640" height="360"
                      frameborder="0"
                      webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
            </div>

          </div>

        </div>

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SECTION -->


  <!-- =========================
       SCREENSHOTS
  ============================== -->
  <section class="screenshots deep-dark-bg" id="screenshot-section">

    <div class="container">

      <!-- SECTION HEADER -->
      <div class="section-header wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

        <!-- SECTION TITLE -->
        <h1 class="white-text">Коктейльная Карта</h1>

        <div class="colored-line">
        </div>
        <div class="section-description">
          Самые лучшие коктейли со всего мира!
        </div>
        <div class="colored-line">
        </div>

      </div>
      <!-- /END SECTION HEADER -->

      <div class="row wow bounceIn animated" data-wow-offset="10" data-wow-duration="1.5s">

        <div id="screenshots" class="owl-carousel owl-theme">


        </div>
        <!-- /END SCREENSHOTS -->

      </div>
      <!-- /END ROW -->

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SCREENSHOTS SECTION -->

  <!-- =========================
       SERVICES
  ============================== -->
  <section class="services " id="services">

    <div class="container">

      <!-- SECTION HEADER -->
      <div class="section-header wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

        <!-- SECTION TITLE -->
        <h1 class="white-text">Мы гарантируем:</h1>

        <div class="colored-line">
        </div>
        <div class="section-description">
          Каждый гость на вашем мероприятии индивидуален, а наша команда профессиональных барменов найдет подход
          к каждому из них, приветливо и внимательно выполнит пожелания.
        </div>
        <div class="colored-line">
        </div>

      </div>
      <!-- /END SECTION HEADER -->

      <div class="row">

        <!-- 1 SERVICE -->
        <div class="col-sm-4 single-service wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">
          <!-- SERVICE ICON -->
          <div class="service-icon">
            <i class="far fa-comments" aria-hidden="true"></i>
          </div>
          <!-- SERVICE HEADING -->
          <h3>Индидуальный подход</h3>
          <!-- SERVICE DESCRIPTION -->
          <p>
            Индидуальный подход к вашим пожеланиям и идеям
          </p>

        </div>
        <!-- /END SINGLE SERVICE -->

        <!-- 2 SERVICE -->
        <div class="col-sm-4 single-service wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SERVICE ICON -->
          <div class="service-icon">
            <i class="fas fa-star" aria-hidden="true"></i>
          </div>

          <!-- SERVICE HEADING -->
          <h3>Качество</h3>

          <!-- SERVICE DESCRIPTION -->
          <p>
            Качество приготовленных авторских и любых классических коктейлей
          </p>

        </div>
        <!-- /END SINGLE SERVICE -->

        <!-- 3 SERVICE -->
        <div class="col-sm-4 single-service wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SERVICE ICON -->
          <div class="service-icon">
            <i class="far fa-handshake" aria-hidden="true"></i>
          </div>

          <!-- SERVICE HEADING -->
          <h3>Адаптивные цены</h3>

          <!-- SERVICE DESCRIPTION -->
          <p>
            Индивидуальный прайс-лист при комплексном заказе услуг
          </p>

        </div>
        <!-- /END SINGLE SERVICE -->

      </div>
      <!-- /END ROW -->
      <div class="row">
        <!-- 4 SERVICE -->
        <div class="col-sm-6 single-service wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SERVICE ICON -->
          <div class="service-icon">
            <i class="far fa-thumbs-up" aria-hidden="true"></i>
          </div>

          <!-- SERVICE HEADING -->
          <h3>Актуальность</h3>

          <!-- SERVICE DESCRIPTION -->
          <p>
            Актуальность и востребованность наших услуг, независимо от формата мероприятия:
            корпоратив, свадьба, юбилей, день рождения, тимбилдинг, девичник, мальчишник...
          </p>

        </div>
        <!-- /END SINGLE SERVICE -->

        <!-- 5 SERVICE -->
        <div class="col-sm-6 single-service wow fadeIn animated" data-wow-offset="10" data-wow-duration="1.5s">

          <!-- SERVICE ICON -->
          <div class="service-icon">
            <i class="fas fa-trophy" aria-hidden="true"></i>
          </div>

          <!-- SERVICE HEADING -->
          <h3>Профессионализм</h3>

          <!-- SERVICE DESCRIPTION -->
          <p>
            В нашей команде только профессиональные бармены. Исполнение бармен-шоу от Чемпиона Беларуси по
            флэйрингу
          </p>

        </div>
        <!-- /END SINGLE SERVICE -->
      </div>

    </div>
    <!-- /END CONTAINER -->

  </section>
  <!-- /END SERVICES SECTION -->


  <!-- =========================
       DOWNLOAD NOW
  ============================== -->
  <section class="download" id="download">

    <div class="color-overlay">

      <div class="container">
        <div class="row">
          <div class="col-xs-12 ">

            <!-- DOWNLOAD BUTTONS AREA -->
            <div class="download-container">
              <!--             <h2 class=" wow fadeInLeft animated" data-wow-offset="10" data-wow-duration="1.5s">Follow
                               us</h2>-->

              <!-- BUTTONS -->
              <div class="buttons wow fadeInRight animated" data-wow-offset="10" data-wow-duration="1.5s">
                <a href="https://vk.com/barman_show_nikanchyk" target="_blank"
                   class="btn btn-default btn-lg standard-button "><i class="fab fa-vk"
                                                                      aria-hidden="true"></i></a>
                <a href="https://www.instagram.com/gena_nikanchik/" target="_blank"
                   class="btn btn-default btn-lg standard-button "><i class="fab fa-instagram"
                                                                      aria-hidden="true"></i></a>
                <p>Позвоните нам</p>
                <a href="tel:+375293846785"
                   class="btn btn-default btn-lg standard-button button-shadow-anim">
                  <img style="width: 20px" src="images/Phone2.png" alt="Viber Gena Nikanchyk">
                  <i class="fas fa-mobile-alt" aria-hidden="true"></i>+375293846785</a>
              </div>
              <!-- /END BUTTONS -->

            </div>
            <!-- END OF DOWNLOAD BUTTONS AREA -->


          </div>
          <!-- END COLUMN -->

        </div>
        <!-- END ROW -->

      </div>
      <!-- /END CONTAINER -->
    </div>
    <!-- /END COLOR OVERLAY -->

  </section>
  <!-- /END DOWNLOAD SECTION -->
  </div>
</template>

<style lang="scss" scoped>

</style>