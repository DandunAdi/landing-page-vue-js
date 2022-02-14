<script setup>
</script>

<template>
<div class="projects">
  <div class="content">
    <h2 class="title">Ongoing projects</h2>
    <div class="action">
      <p class="caption">Turpis facilisis tempor pulvinar in lobortis ornare magna.</p>
      <div class="arrows">
        <div>
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M26.6667 14.6667H10.44L17.8933 7.21337L16 5.33337L5.33334 16L16 26.6667L17.88 24.7867L10.44 17.3334H26.6667V14.6667Z" fill="#AFD4E2"/>
          </svg>
        </div>
        <div>
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M16 5.33337L14.12 7.21337L21.56 14.6667H5.33331V17.3334H21.56L14.12 24.7867L16 26.6667L26.6666 16L16 5.33337Z" fill="#AFD4E2"/>
          </svg>
        </div>
      </div>
    </div>
  </div>
  <div class="project-list">
    <div class="project-item" v-for="item in ['01', '02', '03', '04']" :key="item">
      <img :src="`/src/assets/projects/project${item}.jpg`" alt="">
      <div class="project-item-title">
        <h5>Vintage Villa</h5>
        <div class="project-item-address">
          <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 1C4.065 1 2.5 2.565 2.5 4.5C2.5 7.125 6 11 6 11C6 11 9.5 7.125 9.5 4.5C9.5 2.565 7.935 1 6 1ZM3.5 4.5C3.5 3.12 4.62 2 6 2C7.38 2 8.5 3.12 8.5 4.5C8.5 5.94 7.06 8.095 6 9.44C4.96 8.105 3.5 5.925 3.5 4.5Z" fill="black"/>
            <path d="M6 5.75C6.69036 5.75 7.25 5.19036 7.25 4.5C7.25 3.80964 6.69036 3.25 6 3.25C5.30964 3.25 4.75 3.80964 4.75 4.5C4.75 5.19036 5.30964 5.75 6 5.75Z" fill="black"/>
          </svg>
          <p>2715 Ash Dr. San Jose, Dubai</p>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.projects {
  min-height: 800px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  gap: 84px;

  .title {
    font-size: 48px;
    margin-bottom: 12px;
  }

  .action {
    display: flex;
    justify-content: space-between;

    .caption {
      font-size: 18px;
      color: #BDBDBD;
    }

    .arrows {
      display: flex;
      gap: 12px;
    }
  }

  .project-list {
    display: flex;
    overflow: scroll;
    max-width: 100vw;

    .project-item {
      max-width: 350px;
      position: relative;
      margin-bottom: 40px;
      margin-right: 30px;

      &-title {
        background-color: #fff;
        position: absolute;
        bottom: -40px;
        left: 30px;
        right: 30px;
        padding: 22px 18px;

        h5 {
          font-size: 14px;
        }
      }
      &-address {
        display: flex;
        font-size: 10px;
        margin-top: 6px;
        p {
          margin-left: 4px;
        }
      }
    }
  }

}
</style>