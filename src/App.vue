<template>
  <div class="help-content-area">
    <Header />
    <SearchBarVue />
    <ArticleCards />
    <PopularQuestions />
    <FAQ />
    <ContactSupport />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import SearchBarVue from "./components/SearchBar.vue";
import ArticleCards from "./components/ArticleCards.vue";
import PopularQuestions from "./components/PopularQuestions";
import FAQ from "./components/FAQ.vue";
import ContactSupport from "./components/COntactSupport.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    SearchBarVue,
    ArticleCards,
    PopularQuestions,
    FAQ,
    ContactSupport,
    Footer
  },
};
</script>

<style>
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-thin.woff2)
		format("woff2");
	font-weight: 100;
	font-style: normal;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-light.woff2)
		format("woff2");
	font-weight: 300;
	font-style: normal;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-light-italic.woff2)
		format("woff2");
	font-weight: 300;
	font-style: italic;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-regular.woff2)
		format("woff2");
	font-weight: 400;
	font-style: normal;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-regular-italic.woff2)
		format("woff2");
	font-weight: 400;
	font-style: italic;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-medium.woff2)
		format("woff2");
	font-weight: 500;
	font-style: normal;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-medium-italic.woff2)
		format("woff2");
	font-weight: 500;
	font-style: italic;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-bold.woff2)
		format("woff2");
	font-weight: 700;
	font-style: normal;
}
@font-face {
	font-family: sqmarket;
	src: url(https://cash-f.squarecdn.com/static/fonts/sqmarket/sqmarket-bold-italic.woff2)
		format("woff2");
	font-weight: 700;
	font-style: italic;
}

body {
  font-family: sqmarket, "Helvetica Neue", helvetica, sans-serif;
  min-width: 100%;
  margin: 0;
  padding: 0;
}
body,
figure,
form {
  margin: 0;
}
* {
  box-sizing: border-box;
}

div {
  display: block;
}

@media (max-width: 480px) {
  .help-content-area {
      width: 100%;
      overflow: hidden;
  }
}
@media (max-width: 800px) {
  .help-content-area {
    margin: 0 auto;
    max-width: 100%;
     overflow-x: hidden; 
  }
}
@media (max-width: 1024px) {
  .help-content-area {
    margin: 0 auto;
    max-width: 100%;
     overflow-x: hidden; 
  }
}
.help-content-area {
  max-width: 960px;
  padding-top: 64px;
  margin: auto;
  box-sizing: content-box;
  -webkit-font-smoothing: antialiased;
}

</style>
