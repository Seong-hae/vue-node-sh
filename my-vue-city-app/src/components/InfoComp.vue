<template>
  
  <footer>
      <address>
          서울시 강남구 역삼동 119 뷰엑스B
      </address>
  </footer>
    
</template>

<script>
export default {
  name: 'InfoArea',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- scoped 써주면 다른곳에 같은 이름이 있더라도 여기서 쓰이는걸로 먹히게 해준다 -->
<style scoped>
footer {
    border: 1px solid #ccc;
    text-align: center;
    padding: 20px;
}
</style>
