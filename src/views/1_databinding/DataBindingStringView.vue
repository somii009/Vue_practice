<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
  </div>
</template>
<script>
export default {
  // vue 파일은 함수 생성 시 function 안넣어도 됨
  data() {
    return {
      // key-value 형태로 선언
      userName: 'DataBinding',
      message: 'Welcome',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
</style>
