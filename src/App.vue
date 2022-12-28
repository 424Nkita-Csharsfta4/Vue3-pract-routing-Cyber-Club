<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import TheWelcomeVue from './components/TheWelcome.vue';
import WelcomeItemVue from './components/WelcomeItem.vue';
import ParthNersVue from './components/ParthNers.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  



  <div class="container">
    
  <ul class="nav justify-content-center ">
    <li class="nav-items">
      <img src="./assets/logo-cyber.svg" class="logo" alt="">
    </li>
  <li class="nav-item">
    <RouterLink to="/" class="galpers">Главное</RouterLink>
  </li>
  <li class="nav-item">
    <a href="./views/FormView.vue" class=" galpers">Забронировать</a>
  </li>
  <li class="nav-item">
    <a href="  https://youtu.be/jfKfPfyJRdk" class=" galpers">Live</a>
  </li>
  <li class="nav-item">
    <RouterLink to="/news" class=" galpers">Новости</RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink to="/contact" class=" galpers">Контакты</RouterLink>
  </li>
  <li class="nav-item icons">
    <RouterLink to="/about" class=" galpers icons"><img  class="icons" src="./assets/profile-circle.png" alt=""></RouterLink>
  </li>
  <li class="nav-item icons">
    <RouterLink to="/about" class=" galpers icons"><img class="icons" src="./assets/shopping-cart.png" alt=""></RouterLink>
  </li>
</ul>
 </div>
 <RouterView />
<TheWelcomeVue/>
<WelcomeItemVue/>
<ParthNersVue/>
<FormViewVue/>
<Footer/>
</template>

<style scoped>
.icons:hover{
  color: rgb(238, 177, 65);
  transition: 0.5 ease-out;
}
ul{
  gap: 3em;
  text-decoration: none;
}
.nav-item{
  padding-top: 4px;
}
.galpers:hover{
  color: rgb(255, 52, 52);
  transition: 0.5s ease-in;
}
a{
  text-decoration: none;
  color: antiquewhite;
  margin-top: 2em;
}

.logo{
  width: 140px;
  height: 38px;
}
</style>
