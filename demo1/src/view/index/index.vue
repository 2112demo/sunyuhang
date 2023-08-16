<template>
  <div id="index">
    <h1>{{ msg }}</h1>
    <button v-on-click="count++"></button>
  </div>
</template>

<script>
export default {
    el:"#index",
    data(){
        return{
            msg:"哈哈哈哈",
            count:1
        }
    }
}
</script>

<style>

</style>