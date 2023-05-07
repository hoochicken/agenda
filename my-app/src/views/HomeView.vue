<template>
  <div class="home">
    <!--HelloWorld msg="Das ist ein Property, die kann dann in der HelloWorld-Komponente dargestellt werden"/-->
    <random-ingredient></random-ingredient>
    <random-paraphenalia></random-paraphenalia>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import RandomIngredient from "@/components/RandomIngredient";
import RandomParaphenalia from "@/components/RandomParaphenalia.vue";

export default {
  name: 'HomeView',
  components: {
    RandomParaphenalia,
    // HelloWorld,
    RandomIngredient
  }
}
</script>
