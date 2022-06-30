<template>
  <body>
    <img class="fundo" alt="imagem de fundo" src="../assets/1116781.jpg"/>
    <div class="header">
      <v-navigation-drawer>a</v-navigation-drawer>
    </div>
    <div class="main">main</div>
  </body>
</template>

<style>
  body {
    margin: 0;
    height: 100vh;
    display: grid;
    background-color: #850cff;
    grid-template-columns: 100%;
    grid-template-rows: 15% 85%;
    grid-template-areas:
      "header"
      "main";
  }

  body .fundo {
    width: 100vw;
    height: 100vh;
    background-size: cover;
    position: fixed;
    opacity: 0.8;
  }

  .header {
    grid-area: "header";
    background-color: black;
    opacity: 0.24;
    color: white;
  }

  .main {
    grid-area: "main";
  }
</style>

