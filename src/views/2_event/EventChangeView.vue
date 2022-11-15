<template>
<div>
  <select name="" id="">
    <option value="">** 자동차 선택 **</option>
    <option value="car.code" :key="car.code" v-for="car in carList">{{car.name}}</option>
  </select>

</div>
</template>
<script>

export default {
  name: 'EventChangeView',
  components: {},
  data() {
    return {
      carList: [
        { code: '1', name: 'Volvo' },
        { code: '2', name: 'Saab' },
        { code: '3', name: 'Mercedes' },
        { code: '4', name: 'Audi' }
      ]
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
