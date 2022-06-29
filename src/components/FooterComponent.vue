<template>
  <div>
    <b-navbar toggleable type="dark" variant="danger" class="b-navbar">
        © 2022 Copyright - <a href="https://claudiorogerioteixeira.github.io/portfolio/" target="blank" class="m-1"><b-icon icon="chat-dots"></b-icon> Perguntas & Respostas</a>
    </b-navbar>
  </div>
</template>

<script>
  export default {
    name: 'FooterComponent'
  }

</script>

<style scoped>
 .b-navbar {
    color: #fff;
    width: 100%;
    min-height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    bottom: 0;
    z-index: 1000;
  }

  .b-navbar a {
     text-decoration: none;
     color: white;
  }
</style>