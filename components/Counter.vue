<template>
  <section>
    <h2>Counter App</h2>
    counter: {{ $store.state.counter.counter }}
    <button v-on:click="$store.commit('counter/countUp')">+1</button>
    <button v-on:click="$store.commit('counter/countReset')">reset</button>
  </section>
</template>

<script>
</script>
