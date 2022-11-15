<template>
<div>
  <select name="" id="" v-model="selectedCity">
    <option value="064">제주</option>
    <option value="02">서울</option>
    <option value="031">경기도</option>
    <option value="051">부산</option>
  </select>
</div>
</template>
<script>

export default {
  name: 'DataBindingSelectView',
  components: {},
  data() {
    return {
      selectedCity: '051'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
