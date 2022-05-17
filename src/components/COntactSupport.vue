<template>
  <section class="help-contact-support">
    <h3>Still Need Help?</h3>
    <p>Our customer support is here to help.</p>
    <a class="contact chevron-after" href="/support?category=SOMETHING_ELSE"
      >Contact Support</a
    >
  </section>
</template>

<script>
export default {};
</script>

<style>
.help-contact-support {
	color: #999;
	padding: 24px;
	background: #f8f8f8;
	border-radius: 12px;
    margin-top: 50px;
    margin-bottom: 40px;
}
@media (min-width: 450px) {
	.help-contact-support {
		padding: 42px;
	}
}
.help-contact-support h3 {
	margin-top: 0;
}
.help-contact-support .contact {
	color: #17b500;
}
.help-contact-support .chevron-after:after {
	border: 2px solid #17b500;
	border-top: 0;
	border-left: 0;
	margin-left: 12px;
	top: -1px;
}
.arrow {
	display: inline-block;
	color: #fff;
}
.arrow::before {
	display: block;
	padding-top: calc(100% - 2px);
	border-width: 2px 2px 0 0;
	border-color: currentColor;
	border-style: solid;
	-webkit-transform: rotate(45deg);
	transform: rotate(45deg);
	-webkit-transform-origin: 50%;
	transform-origin: 50%;
}
.arrow--down::before {
	-webkit-transform: rotate(135deg);
	transform: rotate(135deg);
}
.help-article-list .chevron-after:after {
    margin-right: -32px;
    /* float: right; */
    top: 4px;
}
.chevron-after:after {
    display: inline-block;
    width: 10px;
    height: 10px;
    border: 2px solid #ddd;
    border-left: 0;
    border-top: 0;
    position: relative;
    z-index: 1;
    -webkit-transform: rotate(
-45deg
);
    transform: rotate(
-45deg
);
}
.arrow::before, .chevron-after:after, .index-page .marquee-canvas-bitcoin::after, .marquee-canvas .background-video::after {
    content: "";
}


</style>
