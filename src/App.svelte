<script>
	let result = 0, input = 0;

	function add() {
		result += input;
	}

	function subtract() {
		result -= input;
	}

	function multiply() {
		result *= input;
	}

	function divide() {
		result /= input;
	}
</script>

<input type=number bind:value={result}>
<input type=number bind:value={input}>

<button on:click={add}>+</button>
<button on:click={subtract}>-</button>
<button on:click={multiply}>*</button>
<button on:click={divide}>/</button>
