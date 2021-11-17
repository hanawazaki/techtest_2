<template>
  <div class="hero">
    <img src="../assets/img/img-hero1.jpg" class="img1" alt="" />
    <img src="../assets/img/img-hero2.jpg" class="img2" alt="" />
    <div class="hero-text">
      <h1>
        <span>Booked Tool</span> enables you to
        <br />
        create Interactive advertisement
      </h1>
      <a href="#" class="hero-button">What is it?</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  img {
    width: 700px;
  }

  .img1 {
    position: absolute;
    z-index: 10;
  }

  .img2 {
    right: 0;
    z-index: 20;
    position: absolute;
  }

  .hero-text {
    position: absolute;
    z-index: 30;
    left: 25%;
    top: 50%;

    h1 {
      font-size: 1.25rem;
      line-height: 1.75rem;
      color: #757d85;
      margin-bottom: 2rem;
      font-weight: 400;

      span {
        font-weight: 700;
        color: rgb(46, 43, 43);
      }
    }

    .hero-button {
      padding: 1.25rem;
      color: white;
      background-color: #468fcc;
      border-radius: 0.75rem;
      font-weight: 500;
      text-decoration: none;
    }
  }
}
</style>