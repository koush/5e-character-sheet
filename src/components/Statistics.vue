<template>
  <div class="statistics  page">
    <img src="../assets/winston.jpg">
    <h1>{{ name }}</h1>
    <h1>{{ occupation }}</h1>
    <h1>{{ level }}</h1>
    <h1>{{ race }}</h1>
    <h1>{{ alignment }}</h1>
    <p><em>"I'm not saying gnomes are stupid. I'm just saying they lack.. creativity. Heck, anyone can make a mechanical mouse, but a bomb that can flatten a village? Now that's art!"<em></p>
    <p>- Drax a goblin artificer</p>
  </div>
</template>



<script>
export default {
  name: 'statistics',
  data() {
    return {
      alignment: 'Chaotic good',
      name: 'Winston Helldoom Bloodlord',
      occupation: 'Paladin',
      level: '3',
      race: 'Goblin',
    };
  },
};
</script>



<style scoped>



</style>
