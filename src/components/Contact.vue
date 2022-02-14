<script setup>
</script>

<template>
  <div class="contact content">
    <div class="container">
      <img src="@/assets/contact.jpg" alt="">
      <div>
        <div class="title">
          <h2>Contact Us</h2>
          <p>Turpis facilisis tempor pulvinar in lobortis ornare magna.</p>
        </div>
        <form>
          <div class="contact-form">
            <input type="text" placeholder="First name">
            <input type="text" placeholder="Last name">
            <input type="text" placeholder="Email address">
            <input type="text" placeholder="Phone number">
            <textarea name="desc" id="desc" rows="4" placeholder="Description"></textarea>
          </div>
          <div class="contact-send">
            <button class="btn btn-primary">Get a quote</button>
            <p>We don’t sell your email and spam</p>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.contact {
  min-height: 700px;
  display: flex;
  align-items: center;
  .container {
    display: flex;
    gap: 125px;
    .title {
      h2 {
        font-size: 48px;
        margin-bottom: 12px;
      }
      p {
        font-size: 18px;
        color: #BDBDBD;
      }
    }
  }

  &-form {
    margin-top: 40px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    row-gap: 18px;
    column-gap: 30px;
    margin-bottom: 40px;

    textarea {
      grid-column-start: 1;
      grid-column-end: 3;
    }
  }

  &-send {
    display: flex;
    align-items: center;
    gap: 18px;
    p {
      font-size: 12px;
      color: #BDBDBD;
    }
  }

  input, textarea {
    border: 1px solid #1E3240;
    padding: 14px 18px;
    font-family: 'Mulish', sans-serif;
    font-size: 18px;
    resize: none;
    width: 100%;
  }

  ::-webkit-input-placeholder { /* WebKit, Blink, Edge */
    color:    #BDBDBD;
  }
  :-moz-placeholder { /* Mozilla Firefox 4 to 18 */
    color:    #BDBDBD;
    opacity:  1;
  }
  ::-moz-placeholder { /* Mozilla Firefox 19+ */
    color:    #BDBDBD;
    opacity:  1;
  }
  :-ms-input-placeholder { /* Internet Explorer 10-11 */
    color:    #BDBDBD;
  }
  ::-ms-input-placeholder { /* Microsoft Edge */
    color:    #BDBDBD;
  }

  ::placeholder { /* Most modern browsers support this now. */
    color:    #BDBDBD;
  }

  :focus { 
    outline: none !important;
  }
}
</style>