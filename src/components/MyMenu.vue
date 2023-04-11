<template>
  <div class="hello">
    <div v-show="isShow">
      <h1>Menu</h1>
    </div>
    <input type="text" v-model="name" />
    <div>{{ name }}</div>
    <button @click="isShow = !isShow">An/Hien</button>
  </div>
</template>

<script>
export default {
  name: "My-menu",
  data() {
    return {
      name: "phan thanh long",
      isShow: true,
    };
  },
  props: {
    msg: String,
  },
}; 
</script>

<style scoped></style>
