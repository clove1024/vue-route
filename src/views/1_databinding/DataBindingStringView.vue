<template>
<div>
  <h1>{{ message }}</h1>
  <p>{{ userName }}</p>
</div>
</template>

<script>
export default {
  name: 'DataBindingStringView',
  data() {
    return {
      userName: 'John Doe',
      message:
        'Hello, ' +
        this.userName +
        '! Welcome to the Vue.js 2.0 Workshop!'
    }
  }
}

</script>

<style scoped>
</style>
