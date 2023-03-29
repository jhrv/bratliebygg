<nav class="w-full bg-slate-800 p-3 px-10 mb-8">
	<div class="flex justify-between">
		<div class="flex gap-3">
			<a href="/">
				<img alt="Bratlie Bygg Logo" class="w-30" />
			</a>
		</div>
		<div class="hidden space-x-8 lg:flex">
			<a href="/prosjekter">Prosjekter</a>
			<a href="/om-oss">Om oss</a>
			<a href="/kontakt">Kontakt</a>
		</div>
		<div class="flex lg:hidden cursor-pointer burger">
			<div class="space-y-2">
				<span class="block w-8 h-0.5 bg-slate-600" />
				<span class="block w-8 h-0.5 bg-slate-600" />
				<span class="block w-8 h-0.5 bg-slate-600" />
			</div>
		</div>
	</div>
</nav>

<style lang="postcss">
	.burger:hover > div > span {
		@apply bg-slate-400;
	}
</style>
