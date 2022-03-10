<template>
  <div class="hello">
    ThinkTank ^_^ 
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
    font-weight: 500;
    font-size: 24px;
    color: blueviolet;
  }
</style>
