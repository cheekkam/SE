<template>
  <div>
  <v-toolbar color="#E0E0E0">
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>Title</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat router-link to="./Signup">Sign up</v-btn>
      <v-btn flat router-link to="./Login">Log in</v-btn>
      <br><br><br><br><br><br><br><br><br><br>
      <br><br><br><br><br><br><br><br><br><br>
      <br><br><br><br><br><br><br><br><br><br>
    </v-toolbar-items>
  </v-toolbar>
  <router-view></router-view>
  </div> 
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Slide from './Slide'
import Login from './Login'
import Signup from './Signup'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
