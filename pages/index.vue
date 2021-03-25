<template>
  <div class="w-screen h-screen flex justify-center items-center">
<bouton-accueil texte="Awesome Button" tailwindbg="bg-purple-400"/>
<bouton-accueil texte="Awesome Button" tailwindbg="bg-purple-200"/>
  </div>
</template>

<script>
import boutonAccueil from '../components/boutonAccueil.vue'
export default {
  components: { boutonAccueil },}
</script>

<style>
</style>
