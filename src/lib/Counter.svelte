<script>
  let notcount = 0
  const increment = () => {
    notcount += 1
  }
  console.log("yeeyy")
</script>

<button on:click={increment}>
  count is {notcount}
</button>

