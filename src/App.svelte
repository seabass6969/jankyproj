<script lang="ts">
</script>

<main>
	<div class="gridbox">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
</main>

<style lang="scss">
	@keyframes spinning {
		0%{
			transform: rotate(0deg);
		}
		100%{
			transform: rotate(360deg);
		}
	}
	.box {
		width: 100px;
		height: 100px;
		border-color: aqua;
		border-width: 10px;
		margin: 30px;
		border-style: solid;
		border-radius: 10px;
		animation: both 10000ms spinning infinite linear;
	}
	.gridbox {
		display: grid;
		grid-template-columns: auto auto auto auto auto;
	}
</style>