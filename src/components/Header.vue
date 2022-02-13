<script setup>

</script>

<template>
<div class="header">
  <img src="../assets/hero.png" class="hero-img" alt="">
  <div class="content">
    <nav>
      <h4 class="logo">LUGAR</h4>
      <ul>
        <li>HOME</li>
        <li>ABOUT</li>
        <li>PROJECT</li>
        <li>CONTACT</li>
      </ul> 
    </nav>
    <div class="intro">
      <h1>A home is built with love and dreams</h1>
      <p>Real estate farm that makes your dreams true</p>
      <div>
        <button class="btn btn-primary">Our projects</button>
        <button class="btn btn-secondary">Contact Us</button>
      </div>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.header {
  background-color: #AFD4E2;
  min-height: 100vh;
  position: relative;

  .hero-img {
    position: absolute;
    right: 0;
    bottom: 0;
    z-index: 1;
  }
  .content {
    position: relative;
    z-index: 2;
  }

  nav {
    display: flex;
    justify-content: space-between;
    padding-top: 46px;

    ul {
      display: flex;
      gap: 72px;
      list-style: none;
    }
    .logo {
      font-size: 18px;
    }
  }

  .intro {
    margin-top: 109px;

    h1 {
      font-size: 90px;
      max-width: 635px;
      margin-bottom: 18px;
    }
    p {
      font-size: 18px;
      margin-bottom: 32px;
    }

    .btn-secondary {
      margin-left: 30px;
    }
  }
}

</style>