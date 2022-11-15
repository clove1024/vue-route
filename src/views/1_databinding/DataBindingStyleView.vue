<template>
<div>
  <div style="color: red; font-size: 30px;">{{ message }}</div>
  <div :style="style2">스타일 바인딩: 글씨는 green, 폰트크기: 30px</div>
  <button @click="style2.color='blue'">Change Style</button>
</div>
</template>
<script>

export default {
  name: 'DataBindingStyleView',
  components: {},
  data() {
    return {
      style1: {
        color: 'darkblue',
        fontSize: '50px'
      },
      style2: {
        color: 'limegreen',
        fontSize: '40px'
      },
      message: 'Hello World',
      message2: '사랑하는 clove'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
