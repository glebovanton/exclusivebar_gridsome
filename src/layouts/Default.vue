<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Default",
  data() {
    return {};
  },
  created() {
  },
  mounted() {
    window?.addEventListener("scroll", this.handleScroll);
  },
  destroyed() {
    window?.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll(): void {
      const buttonScrollTop = 50;
      const upScroll = this.$refs.upScroll as HTMLElement;
      if (upScroll) {
        if (
          document?.body?.scrollTop > buttonScrollTop ||
          document?.documentElement?.scrollTop > buttonScrollTop
        ) {
          upScroll.style.opacity = "1";
          upScroll.style.visibility = "visible";
        } else {
          upScroll.style.opacity = "0";
          upScroll.style.visibility = "hidden";
        }
      }
    },
    scrollToTop() {
      if (document.body) document.body.scrollTop = 0; // For Safari
      if (document.documentElement) document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
    },
  },
});
</script>

<template>
  <div class="layout">
    <header class="header">
      <nav class="nav">
        <g-link class="nav__link" to="/">Главная</g-link>
        <g-link class="nav__link" to="/#brief0">Выездной &nbsp; бар</g-link>
        <g-link class="nav__link" to="/#brief1">Бармен шоу</g-link>
        <g-link class="nav__link" to="/#brief2">Пирамида из бокалов</g-link>
        <g-link class="nav__link" to="/#brief3">Аренда</g-link>
        <g-link class="nav__link" to="/#screenshot-section"
          >Коктейльная Карта</g-link
        >
        <g-link class="nav__link" to="/#download">Контакты</g-link>
        <g-link class="nav__link" to="/blog/">Блог</g-link>
        <g-link class="nav__link" to="/halloween/">Halloween</g-link>
        <g-link class="nav__link" to="/na-23-fevralia/">23 февраля</g-link>
        <g-link class="nav__link" to="/na-8-marta/">8 марта</g-link>
      </nav>
    </header>
    <slot />
    <g-link id="backScroll" class="backScroll" to="/" />
    <button
      ref="upScroll"
      id="upScroll"
      class="upScroll"
      @click="scrollToTop"
    ></button>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss">
/* FONT FACE LOADER */
/*@font-face {
    font-family: TTDrugs-Thin; !* Имя шрифта *!
    src: url('../fonts/TTDrugs-Thin.otf');
}*/
@font-face {
  font-family: "TTDrugs-Thin";
  src: url("/fonts/TTDrugs-Thin.eot");
  src: url("/fonts/TTDrugs-Thin.eot?#iefix") format("embedded-opentype"),
    url("/fonts/TTDrugs-Thin.woff2") format("woff2"),
    url("/fonts/TTDrugs-Thin.woff") format("woff"),
    url("/fonts/TTDrugs-Thin.ttf") format("truetype"),
    url("/fonts/TTDrugs-Thin.svg#TTDrugs-Thin") format("svg");
  font-weight: 100;
  font-style: normal;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  @font-face {
    font-family: "TTDrugs-Thin";
    src: url("/fonts/TTDrugs-Thin.svg#TTDrugs-Thin") format("svg");
  }
}

body {
  background: #232323;
  font-family: "TTDrugs-Thin", sans-serif;
  font-size: 16px;
  font-weight: 300;
  color: #c8c8c8;
  line-height: 28px;
  text-align: center;
  overflow-x: hidden !important;
  //font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin: 0;
  padding: 0;

  h3 {
    font-size: 24px;
    line-height: 38px;
    font-weight: 300;
    text-shadow: 0 0 3px black;
  }

  .standard-button,
  .standard-button2 {
    font-size: 18px;
    font-weight: 400;
    border-radius: 4px;
    text-shadow: none;
    background: #b5894a;
    color: #ffffff;
    min-width: 70px;
    border: none;
    padding: 16px 16px 16px 16px;
    margin: 5px;
    -webkit-transition: all ease 0.25s;
    transition: all ease 0.25s;
  }

  .layout {
    /*max-width: 760px;*/
    margin: 0 auto;
    position: relative;

    .header {
      position: fixed;
      z-index: 2;
      top: 0;
      left: 0;
      width: 100%;
      margin-right: auto;
      margin-left: auto;
      padding-right: 15px;
      padding-left: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: rgba(0, 0, 0, 0.45);
      min-height: 60px;
      border: none;
      -webkit-backface-visibility: hidden;
      -webkit-box-shadow: 0 2px 8px 0 rgb(50 50 50 / 8%);
      box-shadow: 0 2px 8px 0 rgb(50 50 50 / 8%);

      .nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        width: 100%;
        &__link {
          line-height: 30px;
          font-weight: 400;
          font-size: 13px;
          text-transform: uppercase;
          color: #c8c8c8;
          padding: 15px;
          text-decoration: none;
        }
      }
    }

    a {
      text-decoration: none;
    }

    button {
      border: none;
      margin: 0;
      padding: 0;
      width: auto;
      overflow: visible;

      background: transparent;

      /* inherit font & color from ancestor */
      color: inherit;
      font: inherit;

      /* Normalize `line-height`. Cannot be changed from `normal` in Firefox 4+. */
      line-height: normal;

      /* Corrects font smoothing for webkit */
      -webkit-font-smoothing: inherit;
      -moz-osx-font-smoothing: inherit;

      /* Corrects inability to style clickable `input` types in iOS */
      -webkit-appearance: none;
    }

    .backScroll,
    .upScroll {
      display: inline;
      opacity: 1;
      position: fixed;
      z-index: 1;
      cursor: pointer;
      border-radius: 5px;
      bottom: 20px;
      width: 48px;
      height: 48px;
      transition: opacity 1s;
      color: #d9a757;
      text-decoration: underline;
    }

    .backScroll {
      right: 75px;
      background: rgba(255, 204, 101, 0.47) url(/images/back-32x32.png) center
        center no-repeat;
    }

    .upScroll {
      visibility: hidden;
      right: 20px;
      background: rgba(255, 204, 101, 0.47) url(/images/up-32x32.png) center
        center no-repeat;
    }
  }
}
</style>
