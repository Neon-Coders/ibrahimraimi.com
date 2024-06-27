<script lang="ts">
	import { projects } from "$lib/data";
</script>

<section class="py-10">
	<h2 class="text-2xl font-light">projects</h2>
	<div>
		<ul class="text-sm">
			{#each projects as project}
				<li class="py-2">
					—
					<a href={project.href} target="_blank">{project.title}</a>
				</li>
			{/each}
		</ul>
	</div>
</section>
