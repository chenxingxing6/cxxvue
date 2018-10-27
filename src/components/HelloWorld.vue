<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<!-- js -->
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Hello World'
    }
  }
}
</script>

<!-- CSS -->
<style scoped>
h1,{
  font-weight: normal;
}
</style>
