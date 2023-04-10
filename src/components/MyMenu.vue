<template>
  <div class="hello">
    <h1>Menu</h1>
    <input  type="text" v-model="name" />
    <div>{{name}}</div>
    
  </div>
</template>

<script>
export default {
  name: 'My-menu',
  data() {
    return {name: 'phan thanh long'}
  },
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>