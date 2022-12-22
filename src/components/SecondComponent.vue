<template>
  <div>
    <h2>{{msg}}</h2>
  </div>

</template>

<script>
  export default {
    name: 'SecondComponent',
    props: {
      msg: {
        type: String,
        required: true
      }
    }
  }
</script>