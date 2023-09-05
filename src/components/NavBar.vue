<template>
<nav class="navbar navbar-expand-md navbar-light fixed-top ">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
            <a class="nav-link" href="#">Experience</a>
            <a class="nav-link" href="#about">About</a>
            <a class="nav-link" href="#">Contact</a>
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
          </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style scoped>
nav{
    margin: 20px 50px;
      background-color: rgba(255, 255, 255, 0.514);
      border-style: solid;
      border-color: transparent;
      border-radius: 15px;
      backdrop-filter: blur(8px);
      backdrop-filter: brightness(10px);
      -webkit-box-shadow: 10px 9px 79px -2px rgba(0,0,0,0.75);
-moz-box-shadow: 10px 9px 79px -2px rgba(0,0,0,0.75);
box-shadow: 10px 9px 79px -2px rgba(0,0,0,0.75);
  }
</style>