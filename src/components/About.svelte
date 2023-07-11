<script>
	import Text from './Text.svelte';
</script>

<div>
	<div class="about__title">
		<Text variant="h4">About</Text>
	</div>
	<div class="about__description">
		<Text variant="h5">
			A Senior Software Developer with six years of experience in developing web and mobile
			applications. I believe that with my experience and knowledge, I can contribute to the success
			of your products.
		</Text>
	</div>
</div>

<style>
	@keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-moz-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-webkit-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-o-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-ms-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}
	.about__title {
		margin-top: 24px;
		color: black;
		border-bottom-width: 3px;
		border-bottom-color: black;
		border-style: solid;
		width: fit-content;
		animation: fadeIn 2s;
		-webkit-animation: fadeIn 2s;
		-moz-animation: fadeIn 2s;
		-o-animation: fadeIn 2s;
		-ms-animation: fadeIn 2s;
	}

	.about__description {
		margin-top: 16px;
		color: black;
		animation: fadeIn 2s;
		-webkit-animation: fadeIn 2s;
		-moz-animation: fadeIn 2s;
		-o-animation: fadeIn 2s;
		-ms-animation: fadeIn 2s;
	}
</style>
