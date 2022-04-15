<template>
  <div class="geral">
  <h1> {{ title }} </h1>
  </div>
</template>


<script>
export default {
  data() {
    return {
      title: "Olá,eu sou"
    }
  }
}
</script>


<style scoped>
.geral{
  margin: 0;
  padding: 0;
}

h1{
  color: white;
  font-size: 30px;
  font-family: 'Inter', sans-serif;
  font-weight: 200;
}

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800&display=swap');
</style>