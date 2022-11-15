<template>
<div>
  <h1>Data Drink List View</h1>
  <div>
    <table>
      <thead>
        <tr>
          <th style="text-align:right">이름</th>
          <th style="text-align:right">가격</th>
          <th style="text-align:right">수량</th>
          <th style="text-align:right">설명</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="drink in drinks" :key="drink.id">
          <td style="text-align:right">{{drink.name}}</td>
          <td style="text-align:right">{{drink.price}}</td>
          <td style="text-align:right">{{drink.qty}}</td>
          <td style="text-align:right">{{drink.description}}</td>
        </tr>
      </tbody>
    </table>

  </div>

</div>
</template>
<script>

export default {
  namme: 'DataBindingListView',
  components: {},
  data() {
    return {
      cities: [
        { name: 'London', country: 'UK', population: '332M' },
        { name: 'Paris', country: 'France', population: '671M' },
        { name: 'Berlin', country: 'Germany', population: '542M' },
        { name: 'Madrid', country: 'Spain', population: '637M' },
        { name: 'Rome', country: 'Italy', population: '765M' }
      ],
      drinks: [
        { name: 'Coca Cola', price: 1.5, qty: 10, description: 'Coca Cola' },
        { name: 'Pepsi', price: 1.5, qty: 10, description: 'Pepsi' },
        { name: 'Sprite', price: 1.5, qty: 10, description: 'Sprite' },
        { name: 'Fanta', price: 1.5, qty: 10, description: 'Fanta' },
        { name: 'Water', price: 1.5, qty: 10, description: 'Water' }
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
