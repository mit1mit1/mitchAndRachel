<script setup lang="ts">
	import Pizza from './Pizza.svelte';
	import Rings from './Rings.svelte';
	import Birby from './Birby.svelte';
	import Saxaphone from './Saxaphone.svelte';
	import GuitarAndFlowers from './GuitarAndFlowers.svelte';
	import AutumnLeaves from './AutumnLeaves.svelte';
	import Fan from './Fan.svelte';
	import ShearingShed from './ShearingShed.svelte';
	import TreeHearts from './TreeHearts.svelte';
	import Cocktail from './Cocktail.svelte';
</script>

<div class="schedule">
	<div class="scheduleBox">
		<div class="iconBox">
			<ShearingShed />
		</div>
		<div class="justify-between">
			<div class="timeBox">11:30am</div>
			<h4>Doors Open</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<Rings />
		</div>
		<div class="justify-between">
			<div class="timeBox">12 noon</div>
			<h4>Ceremony</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<Fan />
		</div>
		<div class="justify-between">
			<div class="timeBox">1pm</div>
			<h4>Group photos and refreshments</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<TreeHearts />
		</div>
		<div class="justify-between">
			<div class="timeBox">1:30pm</div>
			<h4>Lunch and lawn games</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<Birby />
		</div>
		<div class="justify-between">
			<div class="timeBox">2:30pm</div>
			<h4>Speeches</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<Cocktail />
		</div>
		<div class="justify-between">
			<div class="timeBox">3:00pm</div>
			<h4>Dessert and cocktail bar</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<GuitarAndFlowers />
		</div>
		<div class="justify-between">
			<div class="timeBox">3:30pm</div>
			<h4>Jazz on the grass</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<AutumnLeaves />
		</div>
		<div class="justify-between">
			<div class="timeBox">5:00pm</div>
			<h4>End of formalities</h4>
		</div>
	</div>
	~
	<div class="scheduleBox">
		<div class="iconBox">
			<Pizza />
		</div>
		<div class="justify-between">
			<div class="timeBox">7:00pm</div>
			<h4>Informal dinner</h4>
		</div>
	</div>
</div>

<style>
	.iconBox {
		min-width: 90px;
		display: flex;
		justify-content: center;
	}

	.schedule {
		display: flex;
		flex-wrap: wrap;
		flex-direction: column;
		gap: 15px;
		width: 100%;
		justify-content: center;
		align-items: center;
	}

	.scheduleBox {
		display: flex;
		align-items: center;
		gap: 15px;
		text-align: center;
		padding: 5px 15px;
		border-radius: 10px;
		border: rgba(0, 0, 0, 0.2) 1px dashed;
		max-width: 500px;
		min-width: 70%;
		min-height: 90px;
	}

	.justify-between {
		display: flex;
		/* justify-content: space-between; */
		width: 100%;
		align-items: center;
	}

	h4 {
		margin: 0px;
		min-height: 2.5em;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.timeBox {
		min-width: 100px;
	}
</style>
