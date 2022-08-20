<script>
	import Events from './components/Event.svelte';
	import events from './data.json';
</script>


<ul class="steps">
	{#each events as event}
		<Events {event} />
	{/each}
</ul>

<br/><br/><br/>

<div class="overflow-x-auto">
  <table class="table w-full">
    <!-- head -->
    <thead>
      <tr>
        <th></th>
        <th>Title</th>
        <th>Date</th>
        <th>Details</th>
      </tr>
    </thead>
    <tbody>
			{#each events as event, i}
				<tr>
					<th>{i}</th>
					<td>{event.title}</td>
					<td>{event.date}</td>
					<td>{event.details}</td>
				</tr>
			{/each}
    </tbody>
  </table>
</div>
