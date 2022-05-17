<template>
  <section class="help-header">
    <a href="/help">
      <img
        class="cash-app-icon"
        src="https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/region/us/icon-square-cash.svg"
        alt="Cash App"
      />
      <span class="cash-app-text">Cash App</span>
    </a>
    <a
      href="https://status.cash.app"
      target="_blank"
      id="issue-detected"
      rel="noopener"
      style="display: block"
      >Check Status Page</a
    >
    <h1 class="help-title">How Can We Help You?</h1>
  </section>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style>

@media (max-width: 480px) {
.help-content-area section {
    /* margin: 32px; */
    max-width: 100%;
    overflow: hidden;
    margin-top: -20px;
}
}
.help-content-area a, .text-link {
    text-decoration: none;
}
/* icon logo */
@media (max-width: 768px) {
.help-header .cash-app-icon {
    width: 48px;
    height: 48px;
    
}
}

.help-header .cash-app-icon {
    width: 40px;
    height: 40px;
}
img {
    border: 0;
    
}
/* span cash text */
.help-header .cash-app-text {
    font-size: 36px;
    font-weight: 500;
    color: #333;
    padding-left: 16px;
    position: relative;
    top: -8px;
}
@media (max-width: 768px) {
.help-header .cash-app-text {
    display: none;
}

}

/* issue err */
#issue-detected {
    display: none;
    border: 1px solid #ebebeb;
    border-radius: 8px;
    float: right;
    color: #f46e38;
    background: url('https://cash-f.squarecdn.com/ember/415a815aa1530945f191fb7aa7e75505578912e7/assets/images/alert-exclamation.svg') 16px no-repeat;
    background-size: 16px 16px;
    padding: 8px 12px 8px 42px;
    font-size: 15px;
    line-height: 28px;
    text-align: right;
    letter-spacing: .2px;
}

 
/* title */
.help-header .help-title {
    font-size: 32px;
    line-height: 40px;
    margin: .83em 0;
}
.help-content-area h3, .help-header .help-title {
    color: #333;
    font-weight: 500;
    letter-spacing: .2px;
}
.help-content-area {
	max-width: 960px;
	padding-top: 64px;
	margin: auto;
	box-sizing: content-box;
	-webkit-font-smoothing: antialiased;
}
@media (min-width: 960px) {
	.help-content-area {
		padding-top: 128px;
	}
}
.help-content-area h3 {
	font-size: 24px;
	line-height: 32px;
	margin-bottom: 24px;
}
.help-content-area section {
	margin-bottom: 48px;
}
@media (max-width: 480px) {
	.help-content-area {
		padding: 0;
	}
	.help-content-area section {
		margin: 32px;
	}
}
.help-header .help-title {
	font-size: 32px;
	line-height: 40px;
	margin: 0.83em 0;
}
@media (min-width: 768px) {
	.help-header .help-title {
		font-size: 40px;
		line-height: 48px;
	}
}
.help-header .help-breadcrumb {
	position: relative;
	top: -16px;
	color: #999;
	font-size: 16px;
	letter-spacing: 0.2px;
}
.help-header .help-breadcrumb:last-child {
	margin-left: 12px;
}
.help-header .chevron-after:after {
	margin-left: 11px;
}
.help-header .cash-app-icon {
	width: 40px;
	height: 40px;
}
.help-header .cash-app-text {
	font-size: 36px;
	font-weight: 500;
	color: #333;
	padding-left: 16px;
	position: relative;
	top: -8px;
}
@media (max-width: 768px) {
	.help-header .cash-app-icon {
		width: 48px;
		height: 48px;
	}
	.help-header .cash-app-text {
		display: none;
	}
}
</style>
