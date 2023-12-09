<template>
  <p v-if="age <= 18">подросток</p>
  <p v-if="age > 18 & age < 26">молодой человек</p>
  <p v-if="age >= 26">мужчина</p>
</template>

<script>


export default {
  data(){
    return{
      age: +prompt("введите ваш возраст")
    }
  }
  
}
</script>

<style>

</style>
