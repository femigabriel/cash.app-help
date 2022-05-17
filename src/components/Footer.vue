<template>
  <footer class="cash-marketing-footer">
    <div class="social-sites">
      <a
        href="https://twitter.com/cashapp"
        target="_blank"
        rel="noopener noreferrer"
        ><img
          src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/social/twitter-icon.svg"
          alt="Cash App on Twitter"
      /></a>
      <a
        href="https://www.instagram.com/cashapp/"
        target="_blank"
        rel="noopener noreferrer"
        ><img
          src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/social/instagram-icon.svg"
          alt="Cash App on Instagram"
      /></a>
      <a
        href="https://www.facebook.com/SquareCash/"
        target="_blank"
        rel="noopener noreferrer"
        ><img
          src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/social/facebook-icon.svg"
          alt="Cash App on Facebook"
      /></a>
    </div>
    <div class="links-and-copyright">
      <div class="copyright"></div>
      <nav class="cash-marketing-footer-links">
        <a href="https://cash.app/legal/tos" rel="noopener noreferrer">Legal</a>
        <a href="https://squareup.com/legal/licenses" rel="noopener noreferrer"
          >Licenses</a
        >
        <a href="/security">Security</a>
        <a href="/careers">Careers</a>
        <a href="/press">Press</a>
        <a href="/bitcoin">Bitcoin</a>
        <a href="/help">Support</a>
        <a href="https://status.cash.app">Status</a>
        <a href="/contact">Contact Us</a>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
.cash-marketing-footer {
	display: -webkit-flex;
	display: -ms-flexbox;
	display: flex;
	-webkit-flex-direction: column;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-align-items: center;
	-ms-flex-align: center;
	align-items: center;
	padding: 40px 0;
	border-top: 1px solid #d8d8d8;
	font-size: 15px;
	color: #cdcdcd;
	font-weight: 300;
}
.cash-marketing-footer a {
	color: currentColor;
}
.cash-marketing-footer a:hover {
	color: #b3b3b3;
}
.cash-marketing-footer a:active {
	color: #a6a6a6;
}
.cash-marketing-footer .social-sites {
	-webkit-flex: 1 0 auto;
	-ms-flex: 1 0 auto;
	flex: 1 0 auto;
	text-align: center;
	margin-bottom: 25px;
}
.cash-marketing-footer .social-sites a {
	display: inline-block;
}
.cash-marketing-footer .social-sites a:not(:last-child) {
	margin-right: 20px;
}
.cash-marketing-footer .social-sites img {
	height: 20px;
	width: 20px;
}
.cash-marketing-footer .links-and-copyright {
	display: -webkit-flex;
	display: -ms-flexbox;
	display: flex;
	-webkit-justify-content: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-flex-direction: column-reverse;
	-ms-flex-direction: column-reverse;
	flex-direction: column-reverse;
	text-align: center;
	line-height: 2.8;
	max-width: 16rem;
	margin: 0 auto;
}
.cash-marketing-footer .copyright {
	-webkit-flex: 1 0 auto;
	-ms-flex: 1 0 auto;
	flex: 1 0 auto;
}
.cash-marketing-footer .cash-marketing-footer-links a {
	display: inline-block;
	margin: 0 12px;
}
@media (min-width: 600px) {
	.cash-marketing-footer {
		padding-bottom: 80px;
	}
	.cash-marketing-footer .links-and-copyright {
		max-width: 100%;
		margin: 0;
	}
}
@media (min-width: 1277px) {
	.cash-marketing-footer {
		-webkit-flex-direction: row-reverse;
		-ms-flex-direction: row-reverse;
		flex-direction: row-reverse;
		-webkit-justify-content: space-between;
		-ms-flex-pack: justify;
		justify-content: space-between;
		-webkit-align-items: center;
		-ms-flex-align: center;
		align-items: center;
		padding: 23px 0 80px;
	}
	.cash-marketing-footer .links-and-copyright {
		-webkit-flex-direction: row;
		-ms-flex-direction: row;
		flex-direction: row;
	}
	.cash-marketing-footer .cash-marketing-footer-links,
	.cash-marketing-footer .copyright {
		margin-right: 23px;
		margin-left: 0;
	}
	.cash-marketing-footer .social-sites {
		margin-bottom: 0;
	}
}
</style>
