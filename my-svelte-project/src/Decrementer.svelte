<script>
  import {store} from './store.js'

  const decrement = () => {
    store.update(value => value - 1)
  }
</script>

<button on:click={decrement}>-</button>