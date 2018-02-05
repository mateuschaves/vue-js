<template>
    <header>
        <h1> {{ teste }} </h1>
    </header>
</template>
<script>
export default {
  data () {
    return {
      teste:'Vue Ninjas'
    }
  }
}
</script>
<style scoped>
header{
  background: lightgreen;
  padding:10px;
}
h1{
  color:#222;
  text-align: center;
}
</style>
