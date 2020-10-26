<template>
  <div>
    <h1>This is just</h1>
    <h2>{{data}}</h2>
    <button v-on:click="help('Help Sent')" >Send Help</button>
  </div>
</template>
<script>
export default {
  name: "Try",
  props: {data: String},
  methods :{
      help(data)
      {
          alert(data)
      }
  }
}
</script>
