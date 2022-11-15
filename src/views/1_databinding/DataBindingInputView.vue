<template>
  <div>
    <form>
      <label>Username:</label><br>
      <input type="text" v-model="userId" />
      <button @click="myFunction">Submit</button>
      <button @click="cgFunction">Change</button>
    </form>
  </div>
</template>
<script>
export default {
  name: 'DataBindingInputView',
  components: {},
  data() {
    return {
      userId: 'atid1024',
      num1: 0,
      num2: 0,
      num3: 0,
      num4: 0
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    myFunction() {
      console.log(this.userId)
    },
    cgFunction() {
      this.userId = 'zasmin'
    }
  }
}
</script>
