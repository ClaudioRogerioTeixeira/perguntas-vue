<template>
  <div id="main-banner">
      <span class="title">Perguntas & Respostas</span>
      <span class="sub-title">App desenvolvida em VueJs</span>
      <b-col lg="4" class="m-5 mt-3">
        <b-button type="button" variant="danger" to="/perguntas" v-b-tooltip.hover="{ variant: 'secondary' }" title="Acessar Perguntas"><b-icon icon="chat-dots"></b-icon> Perguntas</b-button>
      </b-col>
  </div>
</template>

<script>
  export default {
    name: 'HeroComponent'
  }
</script>

<style scoped>
  #main-banner {
    width: 100%;
    min-height: 460px;
    color: red;

    display: flex;
    flex-direction: column;
    justify-content: center;

    background-image: url('@/assets/montagem.jpg');
    background-size: cover;
    overflow-x: hidden;   
  }

  .title {
    margin-left: 45px;
    margin-top: 40px;
    font-size: 50px;
  }

  .sub-title {
    margin-left: 45px;
    font-size: 30px;
  }

  @media only screen and (max-width: 600px) {
    #main-banner {
      display: flex;
      justify-content: start;
      padding-top: 30px;
      background-image: url('@/assets/heroSmall.jpg');
    }

    .title {
      margin-left: 40px;
      margin-top: 40px;
      font-size: 30px;
    }

    .sub-title {
      margin-left: 40px;
      font-size: 20px;
    }    
  }  
</style>
