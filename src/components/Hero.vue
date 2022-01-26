<template>
  <div class="jumbotron">

    <div class="top">
      <h3> questo è il logo di Vue.js <br>
        cliccaci sopra per scoprire la guida &rarr; </h3>
      <a href="https://vuejs.org/">
        <img src="./assets/logo.png" alt="logo">
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

*{
  padding: 0%;
  margin: 0%;
  box-sizing: border-box;
}

.jumbotron{
  min-height: 120px;
  width: 70%;
  background-color: rgb(152, 152, 152) ;
  border-radius: 25px;
  padding: 20px;
}

h3 {
  text-align: center;
  color: blue;
  text-transform: capitalize;
}

a img{
  width: 30px;
  height: auto;
}


</style>
