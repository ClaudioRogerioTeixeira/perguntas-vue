<template>
  <div>
    <b-navbar toggleable type="dark" variant="danger" class="p-2">
      <b-navbar-brand to="/">
        <img id="logo" src="@/assets/logo.png" alt="Logo"/>
      </b-navbar-brand>

      <b-navbar-toggle target="navbar-toggle-collapse"></b-navbar-toggle>

      <b-collapse id="navbar-toggle-collapse" is-nav>
        <b-navbar-nav class="ml-3">
          <b-nav-item to="/"><b-icon icon="house-door-fill"></b-icon> Home</b-nav-item>
          <b-nav-item to="/perguntas"><b-icon icon="question-circle"></b-icon> Perguntas</b-nav-item>
          <!-- <b-nav-item href="#">Perguntas</b-nav-item> -->
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
  export default {
    name: 'HeaderComponent'
  }

</script>

<style scoped>
  #logo {
    width: 60%;
  }

</style>