<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
 <div>
  <p>
    당신이 배워둬야 할 것

    scss어떻게 연결하는가
      
    vuex 로 mapgetter mapmutation mapstate등 알아보기
      
    사이트 편하게 개꿀빨면서 뭔가 작업하려면 결국 어디론가 값을 보내서 값을 얻어오는 행위를 해야하는데 
    그것을 연습하려면 아마 json샘플데이터같은것을 이용하는것이 유리해보이는것으로 추정
    https://jsonplaceholder.typicode.com/
    위 사이트에서 route에 대해서도 배워볼 수 잇을듯
  </p>
 </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
