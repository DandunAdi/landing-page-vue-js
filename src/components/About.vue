<script setup>
</script>

<template>
<div class="content about">
  <img src="../assets/about.png" alt="">
  <div>
    <h2 class="title">Award winning real estate company in Dubai</h2>
    <p class="caption">Semper arcu mauris aliquam lacus. Massa erat vitae ultrices pharetra scelerisque. Ipsum, turpis facilisis tempor pulvinar in lobortis ornare magna.</p>
    <div class="stats">
      <div>
        <h5>PREVIOUS PROJECTS</h5>
        <h3>34+</h3>
      </div>
      <div>
        <h5>YEARS EXPERIENCE</h5>
        <h3>20y</h3>
      </div>
      <div>
        <h5>ONGOING PROJECTS</h5>
        <h3>12</h3>
      </div>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.about {
  display: flex;
  height: 800px;
  align-items: center;
  gap: 125px;

  .title {
    font-size: 48px;
    margin-bottom: 40px;
  }

  .caption {
    font-size: 18px;
    color: #BDBDBD;
    line-height: 120%;
    margin-bottom: 40px;
  }

  .stats {
    display: flex;
    justify-content: space-between;

    h5 {
      font-size: 14px;
      color: #AFD4E2;
      font-weight: 700;
    }
    h3 {
      font-size: 48px;
      font-weight: 300;
      margin-top: 8px;
    }
  }
}
</style>