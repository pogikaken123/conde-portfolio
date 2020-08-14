<template>
  <div id="app">
 
      <navbardesign/>
        <img id="banner-image" src="https://images.unsplash.com/photo-1510519138101-570d1dca3d66?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1031&q=80">
      <h1> Skills</h1>
      <skillsdesign/>
      <Footerdesign/>
     
    <router-view />

  </div>
</template>

<script>
import navbardesign from './components/Nav'
import Footerdesign from './components/Footer'

import skillsdesign from './components/Skills'
export default {
  components:{
    navbardesign,
    Footerdesign,
    skillsdesign
  },
  


}
</script>
<style>
#app {
  font-family:  Helvetica;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#banner-image{
  width:100%;
  display: flex;

}



/* html,body{
  background-color: lightgray;
} */




</style>
