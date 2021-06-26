<template>
    <nav class="navbar is-light" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="https://bulma.io">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png" width="30" height="28">
        </a>
        <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item">
          <strong> BlogPost App</strong>
          </a>
        </div>
        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <!-- <router-link to="/create" class="button is-link">
                <strong>Create</strong>
              </router-link> -->
              <a class="button is-primary">
                <strong>Giriş</strong>
              </a>
              <a class="button is-link">
                <strong>Üye ol</strong>
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>