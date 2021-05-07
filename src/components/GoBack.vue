<template>
<span class="go_back">
  <button @click="goBack">go back</button>
</span>
</template>

<script>
export default {
  name: "GoBack",
  methods: {
    goBack(){
      return this.$router.go(-1);
    }
  }
};
</script>

<style scoped>
.go_back{
  display: flex;
  cursor: pointer;
}
button{
  border: 0;
}
</style>