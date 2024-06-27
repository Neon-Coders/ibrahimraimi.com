<script lang="ts">
	import { crafts } from "$lib/data";
</script>

<section class="py-10">
	<h2 class="text-2xl font-light">crafts</h2>
	<p class="pb-5 text-base">
		A curturld list of expremental & creative development stuff i do in my free time
	</p>
	<div>
		<ul class="text-sm">
			{#each crafts as craft}
				<li class="py-2">
					—
					<a href={craft.href} target="_blank">{craft.title}</a>
				</li>
			{/each}
		</ul>
	</div>
</section>
