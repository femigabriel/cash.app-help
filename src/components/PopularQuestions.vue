<template>
  <section class="help-home__popular">
    <h3>Popular Topics</h3>
    <div class="help-article-list">
      <a class="help-article-list-item chevron-after" href="/help/1111"
        >Receiving a Payment</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1105"
        >Sending a Payment</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1106"
        >Add Cash</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1012"
        >Cash Out</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1108"
        >Cash Card</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1015"
        >Account Settings</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1014"
        >Cash Boost</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1016"
        >Bitcoin</a
      >
      <a class="help-article-list-item chevron-after" href="/help/1113"
        >Direct Deposit</a
      >
      <a class="help-article-list-item chevron-after" href="/help/5000"
        >Investing</a
      >
      <a class="help-article-list-item chevron-after" href="/help/5640"
        >Tax Reporting for Cash App</a
      >
      <a class="help-article-list-item chevron-after" href="/help/6486"
        >Authorized Users Under 18</a
      >
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.chevron-after:after {
	display: inline-block;
	width: 10px;
	height: 10px;
	border: 2px solid #ddd;
	border-left: 0;
	border-top: 0;
	position: relative;
	z-index: 1;
	-webkit-transform: rotate(-45deg);
	transform: rotate(-45deg);
}
.help-article-list {
	display: -webkit-flex;
	display: -ms-flexbox;
	display: flex;
	-webkit-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
}
.help-article-list .chevron-after {
	display: inline-block;
	width: 100%;
}
.help-article-list .chevron-after:after {
	margin-right: -32px;
	float: right;
	top: 4px;
}
@media (min-width: 768px) {
	.help-contact-support {
		height: 195px;
	}
	.help-article-list .chevron-after {
		width: auto;
	}
	.help-article-list .chevron-after:after {
		margin-left: 18px;
		float: none;
		top: -1px;
	}
}
.help-article-list .help-article-list-item {
	display: inline-block;
	color: #666;
	font-size: 18px;
	line-height: 24px;
	letter-spacing: 0.2px;
	width: 100%;
	padding: 16px 48px 16px 0;
}
@media (min-width: 768px) {
	.help-article-list .help-article-list-item {
		width: 50%;
	}
}

</style>
