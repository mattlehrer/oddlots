<script lang="ts">
	import NicCarter from '$lib/tweets/nic_carter.svelte';
	import SamAntar from '$lib/tweets/sam_antar.svelte';
	import ScottIrwin from '$lib/tweets/scott_irwin.svelte';
</script>

<!-- This example requires Tailwind CSS v2.0+ -->
<ul role="list" class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:grid-cols-3 mx-16">
	<li class="col-span-1 bg-white rounded-lg shadow divide-y divide-gray-200">
		<SamAntar />
	</li>
	<li class="col-span-1 bg-white rounded-lg shadow divide-y divide-gray-200">
		<NicCarter />
	</li>
	<li class="col-span-1 bg-white rounded-lg shadow divide-y divide-gray-200">
		<ScottIrwin />
	</li>

	<!-- More people... -->
</ul>
