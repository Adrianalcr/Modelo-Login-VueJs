 
<template>
  <div class="vue-template">
    <!-- Navigation -->
    <nav
      class="navbar shadow bg-white rounded justify-content-between flex-nowrap flex-row fixed-top"
    >
      <div class="container">
        <img alt="Vue logo" src="./assets/logo.png" width="5%" />
        <a class="navbar-brand float-left" href="#" target="_blank">
          Login Vue.js
        </a>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <router-link class="nav-link pr-3" to="/login">Entrar</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-outline-primary" to="/"
              >Inscrever-se</router-link
            >
          </li>
        </ul>
      </div>
    </nav>

    <!-- Main -->
    <div class="App">
      <div class="vertical-center">
        <div class="inner-block">
          <router-view />
        </div>
      </div>
    </div>

    <!--Footer-->
    <div class="footer">
      <a href="http://www.adrianalima.dev.br">Adriana Lima - Dev Full Stack</a>
    </div>
  </div>
</template>

