<style>
	button {
	  background: rgb(1, 24, 12);
	  color: white;
	  border: none;
	  padding: 8px 12px;
	  border-radius: 2px;
		font-family: "Caveat", cursive;
		font-size: 20pt;
		letter-spacing: 1px;
	}
	button:hover,
	button:active {
	  background: #143b63;
	}
</style>

<script>
	export let href;
	export let Kata;
</script>

<a href={href}>
<button>
  {Kata}
</button>
</a>