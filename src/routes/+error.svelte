<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Status {page.status} — There was a problem</h1>
	<p>{page.error?.message ?? "An unexpected issue occurred while loading Amini's platform."}</p>
	<a href="/">Return to Amini Home</a>
</main>
