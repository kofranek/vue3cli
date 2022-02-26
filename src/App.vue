<template>
<div>
  <strong>{{čítač}}</strong>
</div>
  <div>
    <button v-on:click="inkrementuj">přidej</button>
    <button v-on:click="dekrementuj">uber</button>
  </div>

</template>

<script>
export default {
  name: "App",
  data() {
    return{
      čítač:0
    }
  },
  methods: {
    inkrementuj(){
      this.čítač++
    },
    dekrementuj(){
      this.čítač--
    }
  }

}
</script>

<style scoped>

</style>