<template>
<div>
  <div :class="{'text-red': hasError, 'active': false}"> 클래스 바인딩</div>
</div>
</template>
<script>

export default {
  name: 'DataBindingClassView',
  components: {},
  data() {
    return {
      isActive: false,
      hasError: true
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
<style scoped>
.active {
  background-color: lime;
  font-weight: bold;
}
.text-red {
  color: red;
}
</style>
