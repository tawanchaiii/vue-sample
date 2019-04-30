<template>
  <div id="example">
    <p>ตัวดั้งเดิม: "{{ message }}"</p>
    <p>ตัว reverse: "{{ reversedMessage }}"</p> <br />
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
  data: function () {
    return {
      message: 'Hello'
    }
  },
  computed: {
    // a computed getter
    reversedMessage: function () {
      // `this` points to the vm instance
      return this.message.split('').reverse().join('')
    }
  }
}
</script>