<template>
  <div>
    <h4>{{msg1}}</h4>
    <p>{{msg2}}</p>
  </div>

</template>

<script>
  export default {
    name: 'ThirdComponent',
    props: ['msg1', 'msg2']
  }

</script>

<style>
  h4 {
    color: #ff0000
  }
  p {
    color: rgb(43, 0, 255);
  }
</style>