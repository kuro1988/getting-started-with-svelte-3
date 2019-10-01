<script>
	import { tweened } from 'svelte/motion'
	import { bounceInOut } from 'svelte/easing'
</script>

<h1>The count is {countValue}</h1>
<Incrementer />
<Decrementer />
<Setter />