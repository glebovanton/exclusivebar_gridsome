<script>
import MainPageSections from "../components/MainPageSections";
import Footer from "../components/Footer";
export default {
  metaInfo: {
    title: 'Выездной коктейль бар | Бармен шоу | Барный Кейтеринг',
    description: '+375293577726 Exclusive Bar Catering представляет одно из самых актуальных на сегодняшний день направление в ивент-индустрии - барный кейтеринг',
    siteDescription: '+375293577726 Exclusive Bar Catering представляет одно из самых актуальных на сегодняшний день направление в ивент-индустрии - барный кейтеринг'
  },
  components: {
    Footer,
    MainPageSections
  },
}
</script>

<template>
  <Layout>
    <div class="page-wrapper">
      <div class="main-section">
        <!-- Learn how to use images here: https://gridsome.org/docs/images -->
        <g-image alt="Example image" src="~/favicon.png" width="135" />
        <img style="width: 30%; height: auto; opacity: 0.5;filter: alpha(opacity=50);" src="/images/logoBlack2.png" alt="Exclusive Bar Catering">
        <div id="intro-section-text" class="intro-section-text">
          <h1 style="font-size: larger; display: inline;">«Exclusive Bar Catering» </h1>
          <span class="span-h5" style="font-weight: 100">
                                представляет одно из самых актуальных на сегодняшний день направление в ивент-индустрии - барный кейтеринг.
                        Выездной коктейль бар, бармен шоу, пирамида из бокалов в месте проведения вашего мероприятия.
                        </span>
        </div>
        <a href="#download" class="standard-button"><font-awesome class="icon" :icon="['fa', 'phone']"/>Заказать</a>
      </div>
      <MainPageSections />
      <ul class="nav navbar-nav home-links main-navigation">
        <li class="current"><a href="#home">Главная</a></li>
        <li><a href="#brief0">Выездной &nbsp; бар</a></li>
        <li><a href="#brief1">Бармен шоу</a></li>
        <li><a href="#brief2">Пирамида из бокалов</a></li>
        <li><a href="#brief3">Аренда</a></li>
        <li><a href="#screenshot-section">Коктейльная Карта</a></li>
        <li><a href="#download">Контакты</a></li>
        <li><a target="_blank" href="https://exclusivebar.by/blog.html">Блог</a></li>
        <li><a href="https://exclusivebar.by/halloween.html">Halloween</a></li>
        <li><a href="https://exclusivebar.by/na-23-fevralia.html">23 февраля</a></li>
        <li><a href="https://exclusivebar.by/na-8-marta.html">8 марта</a></li>
      </ul>
      <Footer />
    </div>
  </Layout>
</template>

<style lang="scss" scoped>

@import "/css/styles.css";
@import "/css/responsive.css";


.page-wrapper {

  .main-section {
    background-image:url('/images/bg-1.jpg');
    background-repeat:no-repeat;
    -webkit-background-size:cover;
    -moz-background-size:cover;
    -o-background-size:cover;
    background-size:cover;
    background-position:center;
    padding: 60px 15px 0;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .intro-section-text {
    border-radius: 3px;
    background-color: rgba(0, 0, 0, 0.49);
    -webkit-transition: background-color 2s ease-out;
    -moz-transition: background-color 2s ease-out;
    -o-transition: background-color 2s ease-out;
    transition: background-color 2s ease-out;
    padding: 15px;
  }

  .standard-button{
    margin-top: 30px;

    .icon {
      margin-right: 10px;
    }
  }
}

.home-links a {
  margin-right: 1rem;
}
</style>
