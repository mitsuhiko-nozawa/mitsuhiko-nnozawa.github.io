<template>
  <div>
    <Header></Header>
    <Top></Top>
    <Profile></Profile>
    <Career></Career>
    <Skill></Skill>
    <Contact></Contact>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Top from './components/Top.vue'
import Profile from './components/Profile.vue'
import Career from './components/Career.vue'
import Skill from './components/Skill.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Header,
    Top,
    Profile,
    Career,
    Skill,
    Contact
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}

</style>

