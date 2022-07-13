<script lang="ts">
	import {os, fs} from '@tauri-apps/api'
	import { onMount } from 'svelte';

	onMount(async () => {
		console.log({
			name: await os.arch()
		})

		const files = fs.BaseDirectory


	})

	export let name: string;
</script>


hellow worlddd!!!!