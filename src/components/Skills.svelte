<script>
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>

<div>
	<div class="about__title">
		<Text variant="h4">Skills</Text>
	</div>
	<div class="about__description">
		<div class="skills__container">
			<ul>
				<li>
					<Text variant="span">{locale?.skills1}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills2}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills3}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills4}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills5}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills6}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills7}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills8}</Text>
				</li>
				<li>
					<Text variant="span">{locale?.skills9}</Text>
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
