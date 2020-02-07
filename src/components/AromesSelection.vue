<template>
  <div class="container">
    <div class="arome"><img src='../assets/cereales-0.png' /><span>céréals</span></div>
    <div class="arome"><img src='../assets/fruite-0.png' /><span>fruité</span></div>
    <div class="arome"><img src='../assets/levain-0.png' /><span>levain</span></div>
    <div class="arome"><img src='../assets/torrefie-0.png' /><span>torréfié</span></div>
    <div class="arome"><img src='../assets/fermentee-0.png' /><span>fermenté</span></div>
    <div class="arome"><img src='../assets/acidule-0.png' /><span>acidulé</span></div>
    <div class="arome"><img src='../assets/lacte-0.png' /><span>lacté</span></div>
    <div class="arome"><img src='../assets/epicee-0.png' /><span>épicé</span></div>
  </div>
</template>

<script>
export default {
  name: "AromesSelection",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container {
        display: flex;
        justify-content: space-evenly;
        flex-wrap: wrap;
        font-style: italic;
    }

    .container .arome {
        margin-right: 40px;
        margin-bottom: 40px;
        display:flex;
        flex-direction:column;
    }

    .container .arome img {
        cursor: pointer;
    }

    .container .arome span {
        font-size: 1.2em;
    }
</style>
