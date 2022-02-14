<script setup>
</script>

<template>
<div class="footer">
  <div class="content container">
    <div>
      <h3>LUGAR</h3>
      <ul>
        <li>2118 Thornridge Cir. Dubai, UAE 35624</li>
        <li>+33 415 65356 - 9</li>
        <li>contact@lugar.com</li>
      </ul>
    </div>
    <div class="footer-links">
      <div>
        <h3>QUICK LINKS</h3>
        <ul>
          <li>Home</li>
          <li>About</li>
          <li>Project</li>
          <li>Contact</li>
        </ul>
      </div>
      <div>
        <h3>LEGAL LINKS</h3>
        <ul>
          <li>Terms</li>
          <li>Conditions</li>
          <li>Policy</li>
        </ul>
      </div>
      <div>
        <h3>SOCIAL MEDIA</h3>
        <ul>
          <li>Facebook</li>
          <li>Twitter</li>
          <li>Youtube</li>
          <li>Linkedin</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="content">
    <p class="copy">Copyright @ 2022 Lugar Inc.</p>
  </div>
</div>
</template>

<style lang="scss" scoped>
.footer {
  min-height: 400px;
  background-color: #1E3240;
  color: #BDBDBD;
  position: relative;

  h3 {
    color: #fff;
    font-size: 18px;
  }

  ul {
    list-style: none;
    li {
      margin-top: 12px;
      font-size: 14px;
    }
  }
  .container {
    display: flex;
    justify-content: space-between;
    padding-top: 90px;
  }

  &-links {
    display: flex;
    gap: 75px;
  }
  .copy {
    position: absolute;
    bottom: 45px;
    font-size: 12px;
  }
}
</style>