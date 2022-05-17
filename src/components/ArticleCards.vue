<template>
  <section class="help-article-cards">
        <div class="help-article-card">
          <a href="/help/1108">
            <img src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/marketing/help/tapcard.svg">
            <div class="help-article-card-content">
              <div class="help-article-card-title">Cash Card</div>
              <span class="help-article-card-assurance">A free Visa debit card for your Cash App</span>
            </div>
          </a>
        </div>
        <div class="help-article-card">
          <a href="/help/1113">
            <img src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/marketing/help/dd.svg">
            <div class="help-article-card-content">
              <div class="help-article-card-title">Direct Deposit</div>
              <span class="help-article-card-assurance">Deposit your paycheck directly into Cash App</span>
            </div>
          </a>
        </div>
        <div class="help-article-card">
          <a href="/help/1114">
            <img src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/marketing/help/atm.svg">
            <div class="help-article-card-content">
              <div class="help-article-card-title">Cash from ATMs</div>
              <span class="help-article-card-assurance">Use your Cash Card to make ATM withdrawals</span>
            </div>
          </a>
        </div>
        <div class="help-article-card">
          <a href="/help/1014">
            <img src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/marketing/help/rewards.svg">
            <div class="help-article-card-content">
              <div class="help-article-card-title">Cash Boost</div>
              <span class="help-article-card-assurance">Instant discounts at your favorite merchants</span>
            </div>
          </a>
        </div>
      </section>
</template>

<script>
export default {

}
</script>

<style>
.help-article-cards {
	display: grid;
	grid-gap: 8px;
	grid-template-columns: repeat(2, minmax(auto, 260px));
    margin-top: 50px;
}
.help-article-cards img {
	max-width: 260px;
	width: 100%;
}
.help-article-cards .help-article-card {
	position: relative;
	overflow: hidden;
}
.help-article-cards .help-article-card .help-article-card-content {
	position: absolute;
	width: 100%;
	top: 40%;
}
@media (min-width: 600px) {
	.help-article-cards {
		grid-gap: 24px;
	}
	.help-article-cards .help-article-card .help-article-card-content {
		top: 45%;
	}
    .help-article-cards img {
	max-width: 260px;
	width: 100%;
}
}
.help-article-cards
	.help-article-card
	.help-article-card-content
	.help-article-card-title {
	color: #333;
	font-size: 16px;
	font-weight: 500;
	line-height: 21px;
	letter-spacing: 0.2px;
	margin-left: 18px;
}
@media (min-width: 599px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-title {
		font-size: 18px;
	}
}
@media (min-width: 960px) {
	.help-article-cards {
		grid-template-columns: repeat(4, 1fr);
	}
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-title {
		font-size: 16px;
	}
}
@media (min-width: 1024px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-title {
		font-size: 18px;
	}
}
.help-article-cards
	.help-article-card
	.help-article-card-content
	.help-article-card-assurance {
	display: none;
	color: rgba(0, 0, 0, 0.4);
	font-size: 12px;
	font-weight: 400;
	line-height: 17px;
	letter-spacing: 0.2px;
	max-width: 180px;
	margin: 0 18px;
	padding-top: 6px;
}
@media (min-width: 480px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-assurance {
		display: block;
	}
}
@media (min-width: 599px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-assurance {
		font-size: 14px;
	}
}
@media (min-width: 960px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-assurance {
		font-size: 12px;
	}
}
@media (min-width: 1024px) {
	.help-article-cards
		.help-article-card
		.help-article-card-content
		.help-article-card-assurance {
		font-size: 14px;
	}
}
</style>