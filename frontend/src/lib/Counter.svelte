<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button class="text-2xl bg-gray-900 text-white py-2 px-6 rounded shadow" on:click={increment}>
  Clicks: {count}
</button>

