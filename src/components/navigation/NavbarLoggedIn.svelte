<script>
	import Button from '../Button.svelte';
</script>
<div class="flex flex-col">

<nav class="navbar">
	<main class="container">
		<ul class="navbar-nav flex -ml-2 mr-auto">
			<li class="navbar-item">
				<a href="/" class="navbar-link !p-2">
					<img src="/logo.svg" alt="Brick Hill Logo" class="w-[120px]" />
				</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Play</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Shop</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Community</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Membership</a>
			</li>
			<li class="navbar-item">
				<button class="navbar-link gap-0.5 group w-[38px] !px-0">
					<div
						class="h-[6px] w-[6px] border-[1.5px] border-neutral-100 rounded-full transition-all ease-linear group-hover:bg-neutral-100"
					/>
					<div
						class="h-[6px] w-[6px] border-[1.5px] border-neutral-100 rounded-full transition-all ease-linear group-hover:bg-neutral-100"
					/>
					<div
						class="h-[6px] w-[6px] border-[1.5px] border-neutral-100 rounded-full transition-all ease-linear group-hover:bg-neutral-100"
					/>
				</button>
			</li>
		</ul>
		<ul class="navbar-nav flex">
			<li class="navbar-item">
				<a href="#" class="navbar-link">aeo</a>
			</li>
		</ul>
	</main>
</nav>
<nav class="navbar-bottom">
	<main class="container">
		<ul class="navbar-nav flex mr-auto">
			<li class="navbar-item">
				<a href="/" class="navbar-link">Home</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Trades</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Avatar</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Profile</a>
			</li>
		</ul>
		<ul class="navbar-nav flex">
			<li class="navbar-item">
				<a href="/" class="navbar-link">Settings</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Promocodes</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">Blog</a>
			</li>
			<li class="navbar-item">
				<a href="/" class="navbar-link">aeo</a>
			</li>
		</ul>
	</main>
</nav>
</div>
<style lang="postcss">
	.navbar {
		@apply bg-surface-950 fixed left-0 right-0 py-1;
	}
	.navbar-bottom {
		@apply bg-gray-600 fixed left-0 right-0 py-1;
	}
	.navbar .container {
		@apply flex py-0 items-center;
	}
	.navbar-bottom .container {
		@apply flex py-0 items-center;
		max-width: 65rem;
	}
	.navbar-nav {
		@apply items-center;
	}
	.navbar-item {
		@apply inline-flex justify-center items-center;
	}
	.navbar-link {
		@apply min-h-[34px] rounded-sm flex items-center justify-center py-1 text-neutral-100 transition-all ease-linear px-6 uppercase font-semibold text-sm hover:bg-white/[4%];
	}
</style>
