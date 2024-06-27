<script lang="ts">
	import { socials, posts } from "$lib/data";
</script>

<section class="py-5">
	<h2 class="text-2xl font-light">hey</h2>

	<div>
		<p class="mt-4 text-base">
			I'm a Design Engineer who loves turning ideas into real-world businesses. My passion is
			finding simple, yet impactful solutions that make a difference.
		</p>
	</div>
</section>

<section class="py-5">
	<h2 class="text-2xl font-light">posts</h2>
	<div>
		<ul class="text-sm">
			{#each posts as post}
				<li class="py-2">
					—
					<a href={post.href} target="_blank">{post.title}</a>
				</li>
			{/each}
		</ul>
	</div>
</section>

<section class="py-5">
	<h2 class="text-2xl font-light">Get in touch</h2>
	<div>
		<ul class="text-sm">
			{#each socials as social}
				<li class="py-2">
					—
					<a href={social.href} target="_blank">{social.title}</a>
				</li>
			{/each}
		</ul>
	</div>
</section>
