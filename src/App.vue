<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/etec.png" width="100" height="50" />
    <br><br><br>
  </header>

  <div class="header" style="background-color: rgb(223, 223, 223); width: 710px; height: 670px; border-radius: 3%;">
    <figure style="text-align: center;">
      <br>
      <img src="./assets/post1.jpg" width="700" height="500">
    </figure>

    <h2 style="color: black; margin: 0px 0px 0px 10px;">Curso completo de MySQL!</h2>
    <p style="color: black; margin: 4px 0px 0px 30px;">Comece o curso profissional e gratuito sobre MySQL e vire um 
      profissional por meio de exercícios práticos, você aprenderá sobre as diferentes funções e tópicos fundamentais.</p>
    <br>
    <p style="color: black; text-align: right; margin: 0px 20px 0px 0px">Emily</p>
  </div>
  <br>
  <div class="header" style="background-color: rgb(223, 223, 223); width: 720px; height: 670px; border-radius: 3%;">
    <figure style="text-align: center;">
      <br>
      <img src="./assets/post2.jpg" width="700" height="500">
    </figure>

    <h2 style="color: black; margin: 0px 0px 0px 10px;">Novo curso de JavaScript!</h2>
    <p style="color: black; margin: 4px 0px 0px 30px;">Curso profissional sobre JavaScript, vire um profissional nessa área, tenha 
      aulas com profissionaisna area.</p>
    <br>
    <p style="color: black; text-align: right; margin: 0px 20px 0px 0px">Emily</p>
  </div>
  <br>
  <div class="header" style="background-color: rgb(223, 223, 223); width: 720px; height: 670px; border-radius: 3%;">
    <figure style="text-align: center;">
      <br>
      <img src="./assets/post4.jpg" width="700" height="500">
    </figure>

    <h2 style="color: black; margin: 0px 0px 0px 10px;">Curso gratuito de PHP!</h2>
    <p style="color: black; margin: 4px 0px 0px 30px;">Curso de PHP para pessoas que querem ser um profissional na área.</p>
    <br><br>
    <p style="color: black; text-align: right; margin: 0px 20px 0px 0px">Emily</p>
  </div>
  <br>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
