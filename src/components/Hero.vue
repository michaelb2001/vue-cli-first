<template>
  <div class="jumbotron">

    <div class="top">
      <h3>
        cliccaci qui per scoprire la guida &rarr; </h3>
      <a href="https://vuejs.org/" target="_blank" rel="noreferrer">
        Guida
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
  margin: 0 auto;
  background-color: rgb(152, 152, 152) ;
  border-radius: 25px;
  padding: 20px;
}
.top{
  display: flex;
  justify-content: center;
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
