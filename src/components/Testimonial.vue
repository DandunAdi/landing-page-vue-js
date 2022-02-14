<script setup>
</script>

<template>
<div class="testimonial">
  <div class="content">
    <div class="testimonial-title">
      <h2>Few smiles and comment</h2>
      <p>Turpis facilisis tempor pulvinar in lobortis ornare magna.</p>
    </div>
    <div class="testimonial-body">
      <img src="@/assets/girl.jpg" alt="">
      <div class="main">
        <svg width="50" height="28" viewBox="0 0 50 28" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_15_255)">
          <path d="M11.0729 0.416748H25.6562L15.2778 27.673H0.694443L11.0729 0.416748Z" fill="#AFD4E2"/>
          <path d="M35.3785 0.416748H49.9618L39.5833 27.673H25L35.3785 0.416748Z" fill="#AFD4E2"/>
          </g>
          <defs>
          <clipPath id="clip0_15_255">
          <rect width="50" height="27.7778" fill="white"/>
          </clipPath>
          </defs>
        </svg>
        <h3>Dream house isn’t dream anymore</h3>
        <p class="text">Semper arcu mauris aliquam lacus. Massa erat vitae ultrices pharetra scelerisque. Ipsum, turpis facilisis tempor pulvinar.</p>
        <div class="name">
          <h5>Brooklyn Simmons</h5>
          <h6>Artist</h6>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.testimonial {
  min-height: 700px;
  &-title {
    text-align: center;
    margin-bottom: 78px;
    margin-top: 54px;

    h2 {
      font-size: 48px;
      margin-bottom: 12px;
    }
    p {
      font-size: 18px;
    }
  }

  &-body {
    display: flex;
    gap: 125px;
    align-items: center;
    .main {
      display: flex;
      flex-direction: column;
      gap: 18px;

      h3 {
        font-size: 32px;
      }
      .text {
        font-size: 24px;
        font-weight: 300;
      }
      .name {
        h5 {
          font-size: 24px;
          margin-bottom: 4px;
          font-weight: 600;
        }
        h6 {
          font-size: 18px;
          font-weight: 400;
        }
      }
    }
  }
}
</style>