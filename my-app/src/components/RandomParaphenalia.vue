<template>
  <div>
    <h2>Random Paraphenalia</h2>
    <random-element :items="paraphenalia" :buttonLabel="'Random Paraphenalia'"></random-element>
  </div>
</template>

<script>
import RandomElement from "@/components/RandomElement";
export default {
  name: "RandomParaphenalia",
  components: {RandomElement},
  data: () => {
    return {
      paraphenalia: [
          'candle',
          'skull of goat',
          'oil',
          'chrysalis',
          'griffin\'s egg',
          'basilisk\'s crown',
          'wand',
          'cubus',
          'homunculus',
      ]
    }
  }
}
</script>

<style scoped>

</style>