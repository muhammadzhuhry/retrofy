<template>
  <div class="container nes-container with-title is-dark">
    <div class="nes-container is-dark with-title is-centered left-status is-rounded">
      <p class="title">7UP</p>
      <p>Hero.</p>
      <p class="left-text">HP &nbsp;: 
          <i class="icon nes-icon is-small heart"></i>
          <i class="icon nes-icon is-small heart"></i>
          <i class="icon nes-icon is-small heart"></i>
          <i class="icon nes-icon is-small is-half heart"></i>
     </p>
      <p class="left-text">MP &nbsp;: 23</p>
      <p class="left-text">GLD : 100<i class="nes-icon coin is-small"></i></p>
    </div>
    <div class="nes-container is-dark with-title is-centered right-status is-rounded">
        <p class="title">STATUS</p>
      <p class="left-text">STRENGTH &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: 15</p>
      <p class="left-text">AGILITY &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; : 36</p>
      <p class="left-text">VITALITY &nbsp;&nbsp;&nbsp;&nbsp; : 41</p>
      <p class="left-text">INTELLIGENCE &nbsp;: 7</p>
      <p class="left-text">
        LUCK &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: 6
      </p>
      <p class="left-text">MAX HP &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; : 81</p>
      <p class="left-text">MAX MP &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; : 50</p>
      <p class="left-text">ATTACK POWER &nbsp;: 57</p>
      <p class="left-text">DEFENSE POWER : 87</p>
      <hr>
      <p class="left-text">
        EXP &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1316
      </p>
    </div>
    <div class="nes-container is-dark left-status is-rounded">
      <p class="left-text">E > SWORD</p>
      <p class="left-text">E SHIELD</p>
      <p class="left-text">E AMULET</p>
      <p class="left-text">E CLOTHES</p>
    </div>
  </div>
</template>

<script>
import "nes.css/css/nes.min.css";

export default {};
</script>

<style scoped>
.container {
  width: 650px;
  height: 520px;
  align-content: center;
  margin-left: auto;
  margin-right: auto;
  margin-top: 50px;
  padding: 20px;
}

.left-status {
  float: left;
  width: 220px;
  height: 220px;
}

.right-status {
  float: right;
  width: 360px;
  height: 450px;
}

.left-text {
  text-align: left;
}
</style>