<script>
  import {store} from './store.js'

  const setter = () => {
    store.set(event.target.value)
  }
</script>

<input type='number' on:change={setter}/>