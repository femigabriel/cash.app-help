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
</style>
