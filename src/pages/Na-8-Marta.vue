<script>
import FooterS from "../components/FooterS";

export default {
  name: "Na-8-Marta",
  components: {
    FooterS,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <Layout>
    <section>
      <div class="february-wrap">
        <div class="main-img">
          <a href="tel:+375293846785" class="btn btn-bottom btn-default btn-lg standard-button button-shadow-anim">
            <img style="width: 20px" src="/images/Phone2.png" alt="Viber Gena Nikanchyk">
            <i class="fas fa-mobile-alt" aria-hidden="true"></i>+375293846785</a>
        </div>
        <div class="section">
          <div class="colored-line"></div>
          <h1 class="section_title header1">Exclusive Bar Catering</h1>
          <div class="colored-line"></div>
          <p class="p-default section_title2">Лучший способ поздравить прекрасную половину общества с международным женским - это заказать выездной бар Exclusive Bar Catering прямо к вам в офис. Мы предлагаем варианты
            поздравлений:
          </p>
          <div class="row top-margin60">
            <div class="first-part">
              <div class="feature">
                <div class="icon-container">
                  <span class="number">1</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">
                    Работа выездного бара
                  </h4>
                  <p>
                    Всю подготовку мы берём на себя. У вас в офисе организовываем
                    барную зону с профессиональным барменами, которые готовят вкусные
                    коктейли с красивой подачей.
                  </p>
                </div>
              </div>
              <div class="feature">
                <div class="icon-container">
                  <span class="number">2</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">
                    Барные зоны
                  </h4>
                  <p>
                    Организация барной зоны для проведения мастер-класса. Где вы, под руководством бармена, готовите самостоятельно
                    коктейли для себя и угощаете друг друга.
                  </p>
                </div>
              </div>
            </div>
            <div class="last-part">
              <div class="feature">
                <div class="icon-container">
                  <span class="number">3</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">
                    Индивидуальные подарки
                  </h4>
                  <p>
                    Дополнительно к выездному бару или мастер-классу предлагаем
                    сделать индивидуальные подарки в виде барного инвентаря, исходя из
                    вашего бюджета.
                  </p>
                </div>
              </div>
              <div class="feature">
                <div class="icon-container">
                  <span class="number">4</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">
                    Бармен шоу
                  </h4>
                  <p>
                    Бармен шоу от Чемпиона Беларуси по флейрингу Геннадия Никанчика.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="video-container">
          <iframe
              class="video"
              width="560"
              height="315"
              src="https://www.youtube.com/embed/MFLN-5nIJJg"
              frameborder="0"
              allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
          ></iframe>
        </div>
      </div>
    </section>
    <FooterS />
  </Layout>
</template>

<style lang="scss" scoped>
@import "/css/styles.css";
@import "/css/styles_holiday.css";

.main-img {
  background-image: url('/images/8march.jpg')
}
</style>
