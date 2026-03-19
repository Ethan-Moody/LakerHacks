<script>
	import scheduleImg from '$lib/assets/schedule-export.png';
</script>

<svelte:head>
	<title>Schedule - LakerHacks</title>
	<meta name="description" content="View the schedule for LakerHacks" />
</svelte:head>

<main class="flex min-h-screen flex-col items-center bg-[#0B111F]">
	<div class="w-full max-w-[600px]">
		<img src={scheduleImg} alt="schedule" class="w-full" />
	</div>
</main>
