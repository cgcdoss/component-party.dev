<script>
  let count = $state(0);

  function incrementCount() {
    count++;
  }
</script>

<p>Counter: {count}</p>
<button on:click={incrementCount}>+1</button>
