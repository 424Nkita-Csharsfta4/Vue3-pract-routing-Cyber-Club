<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
//import FormView from '../views/Form.vue'
</script>

<template>

<div class="container">
  <div class="row">
    <div class="col">
      <div class="container">
        <p class="text-left japan">
            サイバークラブ
        </p>
        <h1 class="text-left pc">
            Top PC
        </h1>
        <p class="text-left about">
            Для твоей любимой игры, отзывчивые админы а так-же плата за час низкая.Приходи к нам на долго.При регистрации скидка 15%.
Забронируй ПК для себя заранее!!!
        </p>
        <button id="show-modal"  class="btn-ptimary custom" data-bs-toggle="modal" data-bs-target="#myModal"> <RouterLink to="/form" class=" galpers">Зарегистрироваться<img class="cum" src="../assets/logo-cyber.svg" alt=""></RouterLink></button>
        <div class="container mt-3">

</div>

<!-- The Modal -->
<div class="modal" id="myModal">
  <div class="modal-dialog modal-sm">
    <div class="modal-content">

      <!-- Modal Header -->
      <div class="modal-header">
        <h4 class="modal-title reg">Регистрация</h4>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>

      <!-- Modal body -->
      <div class="modal-body">
        <form class="row g-3">
  <div class="col-md-6">
    <label for="inputEmail4" class="form-label">Эл. адрес</label>
    <input type="email" class="form-control" id="inputEmail4">
  </div>
  <div class="col-md-6">
    <label for="inputPassword4" class="form-label">Пароль</label>
    <input type="password" class="form-control" id="inputPassword4">
  </div>
  <div class="col-12">
    <label for="inputAddress" class="form-label">Адрес</label>
    <input type="text" class="form-control" id="inputAddress" placeholder="Проспект Ленина">
  </div>
 
  <div class="col-md-6">
    <label for="inputCity" class="form-label">Город</label>
    <input type="text" class="form-control" id="inputCity" placeholder="Брянск">
  </div>
  <div class="col-md-4">
    <label for="inputState" class="form-label">Область</label>
    <select id="inputState" class="form-select">
      <option selected>Выберите...</option>
      <option>Тирасполь</option>
      <option>Бендеры</option>
    </select>
  </div>
 
  <div class="col-12">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" id="gridCheck">
      <label class="form-check-label" for="gridCheck">
        Проверить меня
      </label>
    </div>
  </div>
  <div class="col-12">
    <button type="submit" class="btn btn-primary">Войти в систему</button>
  </div>
</form>
      </div>

    </div>
  </div>
</div>
      </div>
    </div>
    <div class="col ">
      <img src="../assets/device.png"  class="img-thumbnail dev" alt="">
    </div>
    </div>
    </div>
    <div class="container">
  <div class="row icons-row">
    <div class="col col-text-img">
      Будь кибером
    </div>
    <div class="col col-text-img">
      <img src="../assets/icons-jp.png" alt="">
    </div>
    <div class="col col-text-img">Будь кибером</div>
    <div class="col col-text-img"><img src="../assets/icons-jp.png" alt=""></div>
    <div class="col col-text-img">
      Будь кибером
    </div>
    <div class="col col-text-img">
      <img src="../assets/icons-jp.png" alt="">
    </div>
    <div class="col col-text-img">Будь кибером</div>
    <div class="col col-text-img"><img src="../assets/icons-jp.png" alt=""></div>
    
  </div>
  </div>

</template>
<style scoped>
.col-text-img{
  margin-top: 2em;
  margin-bottom: 2em;
  color: #ff0101;
}
.icons-row{
  background-color: #1e1e1e;
  border-radius: 5px;
}
@media screen and (min-width: 425px) {
#app{
  padding: 0;
}
label{
  color: #1e1e1e;
}
}
.galpers{
  text-decoration: none;
  color: #FDFDFD;
}
.container{
    margin-top: 6em;
    border-radius: 10px;
}
.dev{
    background-color: inherit;
    border:none;
    width: 100%;
}

.japan{
    color: #61C051;
}
.pc{
    color: #FDFDFD;
    letter-spacing: -0.04em;
font-family: 'Bebas Neue',sans-serif;
font-style: normal;
line-height: 154px;
font-size: 128px;
font-weight: 400;
}
.about{
    
font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 18px;
line-height: 180%;
/* or 32px */

letter-spacing: -0.04em;

color: #ff0101;
}
.reg{
  color: #1e1e1e;
}
.custom{
    background: rgba(202, 64, 64, 0.74);
border: 1px solid #FFFFFF;
font-family: 'Inter';
font-style: normal;
font-weight: 500;
font-size: 21px;
line-height: 170%;
/* identical to box height, or 31px */
width: 453px;
height: 80px;
letter-spacing: -0.04em;

color: #FFFFFF;
}
.custom:hover{
color: #61C051;
background-color: #622a2a;
transition: 0.5s ease-in;
}
.cum{
    width: 166px;
height: 48px;
padding-left: 1em;
}
</style>
