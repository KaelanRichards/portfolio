<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a  href="/">
          <figure class="image is-96x96">
            <img class="is-rounded logo" src="../static/kado.dev-bw-logo.jpg">
          </figure>
        </a>
        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link class="navbar-item" to="/">Work</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
          <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>
<style>
.logo{
  border-radius: 50%;
  padding: 10px;
}
</style>