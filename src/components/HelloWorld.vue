<template>
  <div class="hello">
      <p> {{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
    .hello{
        width: 400px;
        height: 400px;
        margin:  0 auto;
        text-align: center;
        border: 1px solid red;
        font-size: 20px;
    }
p{
    color: red;
}
</style>
