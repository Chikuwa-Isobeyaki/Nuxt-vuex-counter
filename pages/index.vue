<template>
  <section class="container">
    <div>
      <counter></counter>
      <hr>
      <counter></counter>
      <hr>
      <counter></counter>
      <hr>
    </div>
  </section>
</template>

<script>
import counter from '../components/counter.vue'

export default {
  components: { counter },
}
</script>
