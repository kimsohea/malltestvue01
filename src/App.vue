<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
 <div>
  <p>
    당신이 배워둬야 할 것
    <br />
    scss어떻게 연결하는가
    <br />
    vuex 로 mapgetter mapmutation mapstate등 알아보기
    <br />
    사이트 편하게 개꿀빨면서 뭔가 작업하려면 결국 어디론가 값을 보내서 값을 얻어오는 행위를 해야하는데 
    그것을 연습하려면 아마 json샘플데이터같은것을 이용하는것이 유리해보이는것으로 추정
    <br />
    https://jsonplaceholder.typicode.com/
    <br />
    위 사이트에서 route에 대해서도 배워볼 수 잇을듯
    <br />
    vue에서 scss를 따로 빼서 적용하는 방법은 이곳에서
    <br />
    https://ux.stories.pe.kr/256
    <br />
    키워드 검색창은 <a href="https://www.google.com/search?q=vue+css+%ED%8C%8C%EC%9D%BC+%EB%B6%84%EB%A6%AC&newwindow=1&client=firefox-b-d&sxsrf=APwXEdc_9LS7k-YtHzrAgqQDyl4Km2e_Cg%3A1680964018325&ei=snkxZMLAE5W2oASt6bCACQ&oq=vue+css+&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQARgFMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDoKCAAQRxDWBBCwAzoECCMQJzoHCAAQigUQQzoLCAAQgAQQsQMQgwE6CAgAEIAEELEDOgoIABCABBAUEIcCOg0ILhCKBRDHARDRAxBDSgQIQRgAUMUKWPI2YJNwaAhwAXgAgAF2iAHZB5IBAzAuOZgBAKABAcgBCsABAQ&sclient=gws-wiz-serp">여기</a>
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
