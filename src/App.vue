<template>
  <div id="app">
    {{ nome }} {{ idade }}
    <div v-text="nome"></div>
    <input type="text" v-model="nome" placeholder="nome" />
    <input type="text" v-model="idade" placeholder="idade" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      nome: "",
      idade: "",
    };
  },
};
</script>

<style>
input {
  background-color: rgb(225, 127, 255);
  text-align: center;
  border-radius: 10px;
}
</style>