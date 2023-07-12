<script>
	import Text from './Text.svelte';
</script>

<div>
	<div class="about__title">
		<Text variant="h4">Skills</Text>
	</div>
	<div class="about__description">
		<div class="skills__container">
			<ul>
				<li>
					<Text variant="span">HTML, CSS</Text>
				</li>
				<li>
					<Text variant="span">Main Languages: Javascript, Typescript</Text>
				</li>
				<li>
					<Text variant="span">Main Frameworks: NextJS, ReactNative, ReactJS, NestJS</Text>
				</li>
				<li>
					<Text variant="span">Knowledge UI Design, Design System</Text>
				</li>
				<li>
					<Text variant="span">Experience with Web3, Blockchain</Text>
				</li>
				<li>
					<Text variant="span">Experience with Github Actions</Text>
				</li>
				<li>
					<Text variant="span"
						>Experience with AWS (Fargate, Elastic Container Service, S3 Bucket,etc)</Text
					>
				</li>
				<li>
					<Text variant="span">Experience with Cloudflare</Text>
				</li>
				<li>
					<Text variant="span">Can research and work with any libraries, languages</Text>
				</li>
			</ul>
		</div>
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

	.skills__container ul {
		list-style-type: square;
	}
	.skills__container li {
		margin-left: 16px;
	}
</style>
