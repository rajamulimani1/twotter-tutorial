<template>
 <div id="app">
   {{user.username}} user.username
 </div>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      followers: 0,
      user: {
        id: 1,
        username: 'raja.mulimani',
        firstname: 'raja',
        lastname: 'mulimani',
        isAdmin: true
      }
    }
  },
  components: {
    
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
