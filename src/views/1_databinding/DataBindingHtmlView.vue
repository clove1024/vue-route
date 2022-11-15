<template>
  <div>
    <div v-html="htmlString"></div>
  </div>
</template>
<script>

export default {
  name: 'DataBindingHtmlView',
  components: {},
  data() {
    return {
      htmlString: '<p style="color: red">This is an HTML RED string</p>'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
