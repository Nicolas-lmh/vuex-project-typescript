<template>
  <div class="home">
    <img alt="logo le saffre" src="../assets/Lesaffre.png">
    <MainMenu msg="Welcome to Your Personnal Project Trainning"/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainMenu from '@/components/MainMenu.vue'

export default {
  name: 'home',
  components: {
    MainMenu,
  }
}
</script>
