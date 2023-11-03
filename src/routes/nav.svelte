<script>
	import Avatar from './avatar.svelte';
	import Logo from './logo.svelte';
</script>

<div
	class="bg-base-100 text-base-content sticky top-0 z-30 flex h-16 w-full
	justify-center bg-opacity-90 backdrop-blur transition-all
	duration-100 [transform:translate3d(0,0,0)] shadow-sm"
>
	<div class="navbar w-full">
		<div class="container mx-auto">
			<Logo />
			<ul class="menu menu-horizontal px-1">
				<li><a href="/">Home</a></li>
				<li><a href="/about">About</a></li>
				<li><a href="/dashboard">Dashboard</a></li>
			</ul>
			<Avatar />
		</div>
	</div>
</div>
