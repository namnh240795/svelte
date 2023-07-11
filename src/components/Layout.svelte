<script>
	import About from './About.svelte';
	import Avatar from './Avatar.svelte';
	import Contact from './Contact.svelte';
	import Education from './Education.svelte';
	import Hobbies from './Hobbies.svelte';
	import OpenSourceProject from './OpenSourceProject.svelte';
	import Skills from './Skills.svelte';
	import Text from './Text.svelte';
</script>

<div class="layout__container">
	<aside>
		<div class="header">
			<Avatar />
			<div class="role">
				<Text variant="h4">Nguyen Hoai Nam</Text>
				<Text variant="h5">Senior Developer</Text>
			</div>
			<Contact>Phone Number: +84 961832495</Contact>
			<Contact>Date Of Birth: 24/07/1995</Contact>
			<Contact>Email: namnh240795@gmail.com</Contact>
			<Contact>
				Github: <a href="https://github.com/namnh240795" target="_blank">
					https://github.com/namnh240795
				</a>
			</Contact>
			<Contact>Location: Ha Noi, Viet Nam</Contact>
		</div>
		<OpenSourceProject />
		<Hobbies />
	</aside>
	<div class="main">
		<About />
		<Education />
		<Skills />
	</div>
</div>

<style lang="css">
	.layout__container {
		color: antiquewhite;
		display: flex;
		flex-direction: row;
		max-width: 768px;
		margin: auto;
	}

	.layout__container .main {
		flex: 1;
		padding: 16px;
		background-color: antiquewhite;
	}

	.layout__container aside {
		width: 220px;
		background-color: #000000;
		padding: 16px;
		min-height: 100vh;
	}

	.layout__container aside .header {
	}

	.layout__container aside {
	}
</style>
