<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div>
      <router-link to="/contact" class="btn py-5 px-5"> click to enter contact page</router-link>
    </div>
  </div>
</template>

<script>

export default {

}
</script>
<style scoped>
.btn{
  border: 1px solid blue;
  text-decoration-line: none;
  background-color: crimson;
}
</style>
