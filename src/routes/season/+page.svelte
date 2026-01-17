<script>
	import { Calendar, TimeGrid } from '@event-calendar/core';

	let options = $state({
		view: 'dayGridMonth',
		events: [
			// your list of events
		]
	});
</script>

<main>
	<div id="calendar-container">
		<Calendar {options} />
	</div>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		padding: 50px;
	}

	#calendar-container {
		width: 80vw;
	}
</style>
