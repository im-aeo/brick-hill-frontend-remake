<script lang="ts">
	import '$src/app.postcss';
	import NavbarLoggedIn from '$src/components/navigation/NavbarLoggedIn.svelte';
	import Footer from '$src/components/navigation/Footer.svelte';
</script>

<NavbarLoggedIn />
<main class="container">
	<slot />
</main>
<Footer />
