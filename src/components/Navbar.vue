<template>

  <nav class="navbar fixed-top navbar-light" style="background-color: #DDF7F2;">

  <div class="container-fluid">
    <span class="navbar-text">  
      Natalia Araya | FrontEnd Developer 
    </span>
    
    
<ul>
     <div class="nav-item">
    <router-link class="nav-link" to="/">Home</router-link>
     </div>
     <div class="nav-item">
     <router-link class="nav-link" to="/Portafolio">Portafolio</router-link>
     </div>
</ul>
    
    
</div>
</nav>

</template>

<script>
export default {

}
</script>

<style scoped>

nav {
  box-shadow: 2px 2px 5px 0;
  /* border-radius: 10px; */
  font-family: 'Quicksand', sans-serif;
  font-size: 20px;
  padding: 0 124px 0 124px;
}

ul {
    display: flex;
    align-items: flex-end;
    
}
.nav-item {

  color: grey;
 
}

.nav-link {

  color: grey;
}


.nav-link:focus, .nav-link:hover {
    color: #eed5ee;
}


</style>



