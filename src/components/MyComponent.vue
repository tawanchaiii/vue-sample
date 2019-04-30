<template>
  <div>
      {{ msg }}
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
  props: [
    'msg'
  ]
}
</script>
<style>
  #helloText {
    color: #178bff;
  }
</style>