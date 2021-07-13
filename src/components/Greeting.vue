<template>
  <p>{{ msg }}</p>
</template>

<script>
export default {
   name: "Greeting",
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