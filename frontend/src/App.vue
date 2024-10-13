<template>
  <div>
    <h1>掲示板</h1>
    name
    <div><input type="text" v-model="name"></div>
    
    Comment
    <div><textarea type="text" v-model="comment"></textarea></div>
    <br>
    <button @click="submitPosts">投稿する</button>
    <br><br>
  </div>
</template>

<script>
export default {
  data(){
    return{
      name: '',
      comment: ''
    }
  },
  methods:{
    submitPosts(){
      console.log("submit!");
    }
  }
}
</script>

// <!-- <template>
//   <div id="app">
//     <img alt="Vue logo" src="./assets/logo.png">
//     <HelloWorld msg="Welcome to Your Vue.js App"/>
//   </div>
// </template>

// <script>
// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }
// </script>

// <style>
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
//   margin-top: 60px;
// }
// </style> -->
