
<template>
  <div>
      Counter: {{ counter }} <br />
      <button type="button" v-on:click="increase()">Click to increase</button>
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
  data: function () {
    return {
      counter: 0
    }
  },
  methods: {
    increase: function () {
      this.counter++
    }
  }
}
</script>
