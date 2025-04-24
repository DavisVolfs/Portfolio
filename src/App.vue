<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header class="header">
    <img alt="me" class="logo" src="./assets/me.png" width="125" height="125" />
    <div class="navi">
    <a class="button1" href="https://www.w3schools.com">ABOUT ME</a>
    <br>
    <a class="button2" href="https://www.w3schools.com">EDUCATION</a>
    <br>
    <a class="button3" href="https://www.w3schools.com">WORK EXPERIENCE</a>
    <br>
    <a class="button4" href="https://www.w3schools.com">SKILLS</a>
    <br>
    <a class="button5" href="https://www.w3schools.com">PROJECTS</a>
    <br>
    <a class="button6" href="https://www.w3schools.com">CONTACT ME</a>
    <br>
    <a class="button7" href="https://www.w3schools.com">FOLLOW ME</a>
    </div>
    <div class="wrapper">
      <HelloWorld msg="ABOUT ME" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

a {
    text-decoration: none;
    color:rgba(14, 5, 89, 1);
}
a:hover {
    color: white;
}

.logo {
  display: block;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    background-color:rgba(246, 185, 19, 1);
  }

  .logo {
    margin-top: -5160px;
    margin-left: 10px;
    margin-right: -45px;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    background: linear-gradient(180deg,rgba(48, 48, 48, 1) 0%, rgba(97, 97, 97, 1) 34%, rgba(227, 227, 227, 1) 70%, rgba(255, 255, 255, 1) 100%);}
   }

   .navi{
   text-align: end;
   width: 240px;
   height: 200px;
   margin-top: -4600px;
   margin-left: -140px;
   margin-right: 0px;
   }

    </style>