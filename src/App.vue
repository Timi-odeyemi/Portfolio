<template>
<header>
  <nav-bar />
</header>

  <section id="home">
    <div class=" container ">
            <div class="row align-items-center ">
              <div class="col-md-6 ">
                <h1 class="display-3 ">Hi,✋🏽</h1>
                <h2 class="display-5 ">I am Odeyemi Timilehin</h2>
              </div>
              <div class="col-sm-6">
                <kinesis-container class="">
      <kinesis-element :strength="50">
        <img class=" rounded mx-auto d-block img-fluid" style="height: 200px; width: 200px ;" src="../src/assets/avatar.png">
      </kinesis-element>
      </kinesis-container>
              </div>
            </div>
          </div>
  </section>
  <section id="about">
    <h1>HI</h1>
  </section>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from "./components/NavBar.vue"

export default{
  components:{
    NavBar,
    HelloWorld,
  }
}
</script>


<style>
#app {

  text-align: center;
  color: #2c3e50;
}

#home {
	background: linear-gradient(205deg, #c31432, #1b0829);
	background-size: 400% 400%;
	animation: gradient 9s ease infinite;
	height: 100vh;
}

@keyframes gradient {

    0%{background-position:66% 0%}
    50%{background-position:35% 100%}
    100%{background-position:66% 0%}
}

#home .container{
color: white;
      /* Center vertically and horizontally */
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
  section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
