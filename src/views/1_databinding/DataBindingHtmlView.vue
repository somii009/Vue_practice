<template>
  <div>
    <div>{{ HTMLString }}</div>
    //문자열로 추가
    <div v-html="HTMLString"></div>
    //html 태그로 추가
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      HTMLString: '<p style="color:red;">빨간색 문자</p>'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
