<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button class="" on:click={increment}>
  Count is {count}
</button>
