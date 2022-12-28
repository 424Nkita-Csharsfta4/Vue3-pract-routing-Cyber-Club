<script lang="ts">
import ParthNersVue from './ParthNers.vue';
import FormView from './ParthNers.vue'
</script>
<template>
 <div class="container scrum">
    <div class="col">
        <h1 class="text-left cyber">
            CyberClub
        </h1>
        <p class="text-left cub">
            ЭТО   НЕ   ТОЛЬКО   ЭЛИТНЫЙ   КОМПЬЮТЕР НЫЙ   КЛУБ   НОВОГО   ПОКОЛЕНИЯ,НО   И КОМАНДА   ПРОФЕССИОНАЛЬНЫХ <span> АДМИНИСТРАТОРОВ</span>
        </p>
    </div>
    <div class="col sliders">
        
      <div id="custCarousel" class="carousel slide" data-ride="carousel" align="center">
        <!-- slides -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/1.png" alt="Hills">
          </div>

          <div class="carousel-item">
            <img src="../assets/2.png" alt="Hills">
          </div>

          <div class="carousel-item">
            <img src="../assets/3.png" alt="Hills">
          </div>

          <div class="carousel-item">
            <img src="../assets/4.png" alt="Hills">
          </div>
        </div>

        <!-- Left right -->
        <a class="carousel-control-prev" href="#custCarousel" data-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#custCarousel" data-slide="next">
          <span class="carousel-control-next-icon"></span>
        </a>

        <!-- Thumbnails -->
        <ol class="carousel-indicators list-inline">
          <li class="list-inline-item active">
            <a id="carousel-selector-0" class="selected" data-slide-to="0" data-target="#custCarousel">
              <img src="../assets/1.png" class="img-fluid">
            </a>
          </li>

          <li class="list-inline-item">
            <a id="carousel-selector-1" data-slide-to="1" data-target="#custCarousel">
              <img src="../assets/2.png" class="img-fluid">
            </a>
          </li>

          <li class="list-inline-item">
            <a id="carousel-selector-2" data-slide-to="2" data-target="#custCarousel">
              <img src="../assets/3.png"  class="img-fluid">
            </a>
          </li>

           <li class="list-inline-item">
            <a id="carousel-selector-2" data-slide-to="3" data-target="#custCarousel">
              <img src="../assets/4.png"  class="img-fluid">
            </a>
          </li>
         </ol>
      </div>
    </div>
    </div>
    <div class="container grow">
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
  <ParthNersVue/>
  <FormView/>
</template>

<style scoped>
.grow{
    margin-top: 3em;
}
.col-text-img{
  margin-top: 2em;
  margin-bottom: 2em;
  color: #ff0101;
}
.icons-row{
  background-color: #1e1e1e;
  border-radius: 5px;
}
.scrum{
    display: flex;
    background-image: url('../assets/cs.jpg');
    margin-top: 3em;
    border-radius: 5px;
}
.sliders{
    width: 600px;
    margin-top: 2em;
    
}
.carousel-inner img {
      width: 20%;
      height: 10%;
  }

#custCarousel .carousel-indicators {
    position: static;
    margin-top:20px;
}

#custCarousel .carousel-indicators > li {
  width:50px;
}

 #custCarousel .carousel-indicators li img {
    display: block;
    opacity: 0.5;
 }

  #custCarousel .carousel-indicators li.active img {
    opacity: 1;
  }

  #custCarousel .carousel-indicators li:hover img {
    opacity: 0.75;
  }

  .carousel-item img{

    width:80%;
  }
span{
    color: #D6001C;
}
.cub{
    width: 659px;
height: 240px;

    font-family:'Times New Roman', Times, serif;
font-style: normal;
font-weight: 400;
font-size: 40px;
line-height: 48px;
letter-spacing: -0.04em;

color: #FFFFFF;
}
.col{
    margin-top: 2em;
}
.cyber{
    font-family: 'Bebas Neue',sans-serif;
font-style: normal;
font-weight: 400;
font-size: 128px;
line-height: 154px;
letter-spacing: -0.04em;

color: #D6001C;
}
</style>
