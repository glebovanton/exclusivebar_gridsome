<script>
export default {
  name: "Halloween",
  data() {
    return {};
  },
};
</script>

<template>
  <Layout>
    <section>
      <div class="february-wrap">
        <div
          class="main-img right">
          <a
            href="tel:+375293846785"
            class="
              btn btn-bottom btn-default btn-lg
              standard-button
              button-shadow-anim
            "
          >
            <img
              style="width: 20px"
              src="/images/Phone2.png"
              alt="Viber Gena Nikanchyk"
            />
            <i class="fas fa-mobile-alt" aria-hidden="true"></i>+375293846785</a
          >
        </div>
        <div class="section">
          <div class="colored-line"></div>
          <h1 class="section_title header1">
            Хеллоуин вместе с Exclusive Bar Catering
          </h1>
          <div class="colored-line"></div>
          <p class="p-default section_title2">
            У нас готово предложение по работе Выездного Бара у вас в офисе!
            Декор барной стойки создаёт антураж праздника! Специально
            разработанное осеннее меню дополнено элементами Хеллоуина.
          </p>
          <div class="screenshots">
            <div class="container full-width">
              <div
                class="row wow bounceIn animated"
                data-wow-offset="10"
                data-wow-duration="1.5s"
              >
                <div
                  id="decor-screenshots"
                  class="owl-carousel owl-theme"
                ></div>
              </div>
            </div>
          </div>
          <div class="row top-margin60">
            <div class="first-part">
              <div class="feature">
                <div class="icon-container">
                  <span class="number">1</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">Работа выездного бара</h4>
                  <p>
                    Всю подготовку мы берём на себя. У вас в офисе
                    организовываем барную зону с профессиональным барменами,
                    которые готовят вкусные коктейли с жуткой подачей.
                  </p>
                </div>
              </div>
              <div class="feature">
                <div class="icon-container">
                  <span class="number">2</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">Барные зоны</h4>
                  <p>
                    Декор барной стойки подобран в стилистику осеннего
                    праздника. Вам не нужно заказывать его дополнительно, все
                    уже входит в стоимость.
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
                  <h4 class="title header2">Мастер-класс</h4>
                  <p>
                    Желающие могут попробовать себя в роли бармена и приготовить
                    несколько напитков для себя или друзей
                  </p>
                </div>
              </div>
              <div class="feature">
                <div class="icon-container">
                  <span class="number">4</span>
                </div>
                <div class="feature-details">
                  <h4 class="title header2">Индивидуальность</h4>
                  <p>
                    Стоимость просчитывается индивидуально. Для этого необходимо
                    знать количество гостей и продолжительность работы бара.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <section class="screenshots deep-dark-bg">
          <div class="container">
            <div
              class="row wow bounceIn animated"
              data-wow-offset="10"
              data-wow-duration="1.5s"
            >
              <div
                id="cocktails-screenshots"
                class="owl-carousel owl-theme"
              ></div>
            </div>
          </div>
        </section>
      </div>
    </section>
  </Layout>
</template>

<style lang="scss" scoped>
@import "/css/styles.css";

.main-img {
  background-image: url('/images/halloween.jpg')
}
</style>
