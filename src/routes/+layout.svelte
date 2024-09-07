<script>
	import '../app.css';
</script>

<div class="relative flex h-full w-full items-center justify-center">
	<enhanced:img
		class="absolute inset-0 z-0 max-h-full min-h-full min-w-full bg-cover bg-center object-cover opacity-80"
		src="$lib/images/background.jpg"
		sizes="(min-width:1920px) 1280px, (min-width:1080px) 640px, (min-width:768px) 400px"
		fetchpriority="high"
		loading="eager"
		alt="Background"
	/>
	<slot />
</div>
