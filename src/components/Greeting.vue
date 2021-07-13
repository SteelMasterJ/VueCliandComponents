<template>
  <p v-if="age > 24">{{ msg }}</p>
  <p v-else>You must be 25 years or older to view this message</p>
</template>

<script>
export default {
   name: "Greeting",
   props: ["age"],
   data() {
     return {
       msg: "Hello World!"
     }
   },
 };
</script>

<style scoped lang="scss">
$color: dodgerblue;

p {
    color: dodgerblue;
}
</style>