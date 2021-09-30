<script>
export default {
  name: "Cocktails",
  data() {
    return {
      altList: [
        "coctail",
        "коктейль",
        '"exclusive bar"',
        "эксклюзивбар",
        '"эксклюзив бар"',
        "exclusivebar",
        "коктейли",
        '"бар"',
        '"bar"',
        '"кейтеринг"',
        '"catering"',
        '"бармен"',
        '"бармен шоу"',
        '"barman show"',
        '"barmanshow"',
      ],
      cocktails: [
        {
          src: "/images/1_coctails/KAR_1995.jpg",
          title: "Honey Sparkling",
          description:
            "Необыкновенное сочетание медового виски и игристого вина.",
        },
        {
          src: "/images/1_coctails/KAR_2000.jpg",
          title: "Kiwi Chalet",
          description:
            "Свежесть и полезность киви гармонирует с лимончелой и игристым вином.",
        },
        {
          src: "/images/1_coctails/KAR_1845.jpg",
          title: "Fresh flower",
          description:
            "Премиум водка/ джин в сочетании со свежестью базилика и цветов бузины, дополненная горечью тоника.",
        },
        {
          src: "/images/1_coctails/KAR_1871.jpg",
          title: "Basil berry fizz",
          description:
            "Насыщенность малины гармонирует с можжевеловой терпкостью джина и свежестью базилика.",
        },
        {
          src: "/images/1_coctails/KAR_2038.jpg",
          title: "Exclusive Mojito",
          description:
            "Непревзойденный эталон свежести, в сочетании рома, мяты и лайма.",
        },
        {
          src: "/images/1_coctails/KAR_2204.jpg",
          title: "Strawberry Mojito",
          description:
            "Насыщенный клубничный вкус дополняет классический рецепт. Также можно подобрать и ваш любимый аромат.",
        },
        {
          src: "/images/1_coctails/KAR_2016.jpg",
          title: "Tropical nut",
          description:
            "Молочно-ореховый Коктейль с добавлением рома и ананаса.",
        },
        {
          src: "/images/1_coctails/KAR_2057.jpg",
          title: "Mint smash",
          description: "Ром в сочетании с медовым сиропом и мятной пеной.",
        },
        {
          src: "/images/1_coctails/KAR_2081.jpg",
          title: "Daiquiri",
          description:
            "Основой является светлый ром, сок лайма и сахар.Можно добавить ваш любимый вкус.",
        },
        {
          src: "/images/1_coctails/KAR_2067.jpg",
          title: "Pomegranat taste",
          description:
            "Гранатовый вкус переплетён с насыщенностью текилы и сиропа ананас.",
        },
        {
          src: "/images/1_coctails/KAR_2114.jpg",
          title: "Bitterly sweet",
          description:
            "Крепость бренди, горечь Кампари и грейпфрута, сладость маракуйи. Дают горечи и сладости сбалансированность.",
        },
        {
          src: "/images/1_coctails/KAR_2123.jpg",
          title: "Brandy Imperator",
          description:
            "Яркий вкус алычи, гармонирующий с бренди и цитрусовыми.",
        },
        {
          src: "/images/1_coctails/KAR_1949.jpg",
          title: "Almond Wiskey",
          description: "Бескомпромиссное сочетание виски, миндаля и вишни.",
        },
        {
          src: "/images/1_coctails/KAR_1901.jpg",
          title: "Prune sour",
          description:
            "Сочетание виски с черносливом, сбалансированного лимонным соком и белком.",
        },
        {
          src: "/images/1_coctails/KAR_2104.jpg",
          title: "Whiskey hops",
          description: "Пивной Коктейль на основе виски и пюре инжира.",
        },
        {
          src: "/images/1_coctails/KAR_1904.jpg",
          title: "Caramel Oakherd",
          description:
            "Насыщенный вкус пряного Рома и солёной карамели, дополненный попкорном.",
        },
        {
          src: "/images/1_coctails/KAR_2139.jpg",
          title: "Reviver",
          description:
            "Крепкий напиток, в основе которого виски или коньяк, вермут и биттер.",
        },
        {
          src: "/images/1_coctails/KAR_1842.jpg",
          title: "Herb journey",
          description:
            "Премиум водка, мятный ликёр, корица, лемонграсс и грейпфрут.",
        },
        {
          src: "/images/1_coctails/KAR_2147.jpg",
          title: "White Russian",
          description:
            "Премиум водка с кофейным ликером, заправленные пеной из пломбира или сливками.",
        },
        {
          src: "/images/1_coctails/KAR_2176.jpg",
          title: "Martini Royale",
          description:
            "Аперитивная классика сочетания вермута и игристого вина.",
        },
        {
          src: "/images/1_coctails/KAR_2167.jpg",
          title: "Aperol Spritz",
          description:
            "Излюбленный рецепт гармонии Апероля, игристого вина и содовой.",
        },
      ],
    };
  },
};
</script>

<template>
  <Layout>
    <section class="features" id="features">
      <div class="container-fluid">
        <div class="section-header">
          <h2 class="white-text">Коктейльная Карта</h2>

          <div class="colored-line"></div>

          <div class="section-description">
            Самые лучшие коктейли со всего мира!
          </div>
          <div class="colored-line"></div>
        </div>
      </div>
      <div class="container">
        <div class="row" id="coctail_list">
          <div
            v-for="(cocktail, index) in cocktails"
            class="cocktail-wrapper col-xs-12 col-sm-6 col-md-4"
          >
            <div class="coct">
              <img :src="cocktail.src" :alt="altList[index % altList.length]" />
            </div>
            <div class="coct_desc">
              <h3>{{ cocktail.title }}</h3>
              <p>{{ cocktail.description }}</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<style lang="scss" scoped>
@import "/css/styles.css";
@import "/css/styles_coctails.css";
</style>
