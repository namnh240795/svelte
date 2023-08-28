<script>
	import About from './About.svelte';
	import Avatar from './Avatar.svelte';
	import Contact from './Contact.svelte';
	import Education from './Education.svelte';
	import Hobbies from './Hobbies.svelte';
	import OpenSourceProject from './OpenSourceProject.svelte';
	import Skills from './Skills.svelte';
	import Text from './Text.svelte';
	import { getContext } from 'svelte';
	let locale = getContext('locale');
</script>



<div class="text-[antiquewhite] flex flex-row max-w-screen-md m-auto flex-wrap">
	<aside class="md:w-[220px] md:bg-[#000000] p-[16px] md:min-h-screen w-full bg-[rgba(0,_0,_0,_0.25)]">
		<div class="header">
			<Avatar />
			<div class="role">
				<Text variant="h4">{locale?.title}</Text>
				<Text variant="h5">{locale?.description}</Text>
			</div>
			<Contact>{locale?.phoneNumber}: +84 961832495</Contact>
			<Contact>{locale?.dateOfBirth}: 24/07/1995</Contact>
			<Contact>Email: namnh240795@gmail.com</Contact>
			<Contact>
				Github: <a class="text-[#901009]" href="https://github.com/namnh240795" target="_blank">
					https://github.com/namnh240795
				</a>
			</Contact>
			<Contact>{locale?.location}: Hà Nội, Việt Nam</Contact>
			<Contact>
				{locale?.lang}: <a class="text-[#901009]" href={locale?.cvLink} target="_blank">
					{locale?.cvLink}
				</a>
			</Contact>
		</div>
		<OpenSourceProject />
		<Hobbies />
	</aside>
	<div class="flex-[1] p-[16px] bg-[antiquewhite]">
		<About />
		<Education />
		<Skills />
	</div>
</div>

