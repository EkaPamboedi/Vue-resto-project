<template>
<router-view />
<!-- Helloo -->
<!-- <HomePage /> -->
</template>

<script>
  export default {
    name: 'App',
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

.logo{
    width:200px;
    margin-bottom: 0px;
}
.register, .login{
    margin-top: -50px;
}
.register input , .login input {
    width:300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto; 
    margin-left: auto;
    border: 1px solid skyblue;
}
.register button , .login button {
    margin-top: 0%;
    border: 1px solid skyblue;
    height: 30px;
    width: 325px;
    background: skyblue;
    color: #ffffffff;
    cursor: pointer;
}
.register button:hover, .login button:hover {
background-color: steelblue;
}

</style>
