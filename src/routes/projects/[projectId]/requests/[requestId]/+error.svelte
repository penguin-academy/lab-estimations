<script lang="ts">
	import { page } from '$app/stores';
</script>

<h1>Something went wrong: {$page.status}</h1>
<p>Cosito: {$page.error?.message}</p>
