<script>
	import { getContext } from "svelte";

  let locale = getContext('locale')
</script>

<svelte:head>
	<title>{locale?.title}</title>
	<meta property="title" content={locale?.title} />
	<meta property="url" content={locale?.url} />
	<meta name="description" content={locale?.description} />
	<meta property="og:type" content="website" />
	<meta property="og:title" content={locale?.title} />
	<meta property="og:description" content={locale?.description} />
	<meta name="keywords" content={locale?.title} />
	<meta name="author" content={locale?.title} />
	<meta property="og:image" content="https://cv.yellowcandle.party/avatar.jpeg" />
</svelte:head>