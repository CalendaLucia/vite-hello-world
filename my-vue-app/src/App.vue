<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  name:'App',
    data() {
      return {

      };
    },
    components: {
        AppTitle,
        AppHero
    }
}

</script>

<template>

  <AppTitle/>
  <AppHero/>
  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
