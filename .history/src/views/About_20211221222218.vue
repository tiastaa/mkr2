<template>
    <div>
        <Header />
        THIS IS AN ABOUT PAGE 
    </div>
</template>

<script>
import Header from '../components/Header.vue'
    export default {
       name: "About",
       components: {
           Header
       }
    }
</script>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Fira Sans", sans-serif;
}
div{
    text-align: center;
}
</style>