<template>
  <section id="search-bar">
  <div>
    <input type="text" id="search-input-field" class="search-input-field" placeholder="Search" autocomplete="off">
  </div>
  <div id="search-bar-results" class="help-article-body"></div>
</section>
</template>

<script>
export default {

}
</script>

<style>
@media (max-width: 480px) {
.help-content-area section {
    margin: 32px;
}
}
@media (max-width: 480px) {
#search-input-field {
    height: 56px;
    background-position: left 16px top 16px;
}
}

#search-input-field {
    background-color: #f8f8f8;
    background-image: url('https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/icon-search-rounded.svg');
    background-size: 24px;
    background-repeat: no-repeat;
    background-position: left 20px top 20px;
    border: none;
    border-radius: 12px;
    color: #999;
    font-size: 18px;
    height: 64px;
    padding-left: 60px;
    padding-right: 24px;
    width: 100%;
}
button, input {
    line-height: normal;
}
button, input, select, textarea {
    font-family: inherit;
    font-size: 100%;
    margin: 0;
   vertical-align: baseline;
}
#search-bar-results {
    background-color: #f8f8f8;
    border: none;
    border-radius: 12px;
    margin: 24px 0;
    padding: 48px;
    position: relative;
    width: 100%;
    z-index: 100;
    display: none;
}
.help-article-body {
    color: #666;
    letter-spacing: .2;
}
</style>