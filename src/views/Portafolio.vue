<template>
  <div class="container">
    <div class="titulo text-center">
    <h1>SOY EL PORTAFOLIO</h1>
    </div>
<div class="row">
    <div class="card col-md-3">
  <img src="../assets/developer.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-light">Ver más</a>
  </div>
</div>

<div class="card col-md-3">
  <img src="../assets/developer.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-light">Ver más</a>
  </div>
</div>

<div class="card col-md-3">
  <img src="../assets/developer.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-light">Ver más</a>
  </div>
</div>
</div>

<div class="row">
    <div class="card col-md-3">
  <img src="../assets/developer.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-light">Ver más</a>
  </div>
</div>

<div class="card col-md-3">
  <img src="../assets/CafeteríaSass2.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title"><strong>Cafetería SASS</strong></h5>
    <br><p class="card-text">Proyecto SASS. Responsive <br> <a href="https://github.com/natartist/cafeSASS">Ver código</a></p>
    <br><a href="https://natartist.github.io/Cafeteria-Html-Css/" class="btn btn-light">Ver más</a>
  </div>
</div>

<div class="card col-md-3">
  <img src="../assets/cafeteria1.png" class="card-img-top" alt="developer">
  <div class="card-body">
    <h5 class="card-title"><strong>Cafetería HTML y CSS</strong></h5>
    <br><p class="card-text">Proyecto realizado con HTML y CSS. Responsive <br> <a href="https://github.com/natartist/Cafeteria-Html-Css">Ver código</a></p>
    <br><a href="https://natartist.github.io/Cafeteria-Html-Css/" class="btn btn-light">Ver más</a>
  </div>
</div>

</div>


  </div>
</template>

<style scoped>
.container {
  /* background: pink; */
  width: 1000px;
  
  
  
  padding: 100px 40px 40px 40px;
  background-image: url("@/assets/entorno.png");
  background-attachment: fixed;
  background-repeat: repeat;
  background-size: 400px;
}

.row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 40px 30px 0px 30px;
}

.card {
  padding: 10px 10px 10px 10px;
  border-radius: 20px;
  color: #fff;
  font-size: 18px;
  background: rgba(255,255,255,0.1);
  box-shadow: 10px 10px 20px -10px rgba(255, 255, 255, 0.2);
  border-right: 1px solid rgba(255,255,255,0.2);
  border-bottom: 1px solid rgba(255,255,255,0.2);
  backdrop-filter: blur(20px);
  transition: .5s ease;
  width: 250px;
  height: 500px;
  color: gray;
  font-family: "Quicksand", sans-serif;
}

/* .titulo{
  display: flex;
  align-content: center;
  text-align: center;
} */

h1 {
  margin-top: 15px;
  color: gray;
  font-family: "Quicksand", sans-serif;
  text-align: center;
  background-color: white;
  width: 400px;
}
.btn {
background-color: #ddf7f2;
  font-size: 10px;
  border-radius: 8px;
  box-shadow: 2px 2px 5px 0;
  height: 25px;
  margin-bottom: 15px;
  color: gray;
  font-family: "Quicksand", sans-serif;
  }

  .card-img-top {
    border-radius: 15px;
  }
  
  p.card-text {
    font-size: 13px;
  }

  .card {
    height: 425px;
  }
</style>