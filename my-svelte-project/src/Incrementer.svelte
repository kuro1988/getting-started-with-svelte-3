<script>
  import {store} from './store.js'

  const increment = () => {
    store.update(value => value + 1)
  }
</script>

<button on:click={increment}>+</button>