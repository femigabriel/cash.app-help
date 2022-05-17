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
