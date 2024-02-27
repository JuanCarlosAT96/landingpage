<template>
  <section class="hero">
    <div class="hero_title">
      <span class="hero_title_store">Pharmachy Store</span>
      <h1>Your Trusted Pharmacy Store</h1>
      <p class="hero_title_description">
        Libero diam auctor tristique hendrerit in eu vel id. Nec leo amet
        suscipit nulla. Nullam vitae sit tempus diam.
      </p>
      <div class="hero_imagebox">
        <div>
          <img src="../assets/user1.png" alt="" />
          <img src="../assets/user2.png" alt="" />
          <img src="../assets/user3.png" alt="" />
          <img src="../assets/user4.png" alt="" />
        </div>

        <div class="hero_imagebox-text">
          <span>100k+</span>
          <label>Satisfied Customers</label>
        </div>
      </div>
    </div>
    <div>
      <img class="hero_img" src="../assets/heroimg.png" alt="" />
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
  height: 570px;
  display: flex;
  justify-content: space-evenly;
  background: var(--Secondary, #dee9ff);
}

.hero_title {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 40px;
}

.hero_imagebox {
  display: flex;
  align-items: flex-start;
  gap: 10px;
}

.hero_imagebox-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.hero_imagebox-text span {
  color: #d64779;
}

h1 {
  color: var(--Primary, #0d0d0d);

  font-size: 64px;
  font-style: normal;
  font-weight: 600;
  line-height: 120%;
  width: 560px;
  margin: 0;
}

.hero_title_description {
  width: 442px;
  color: var(--Text, #7a7a7a);

  font-size: 16px;
  font-style: normal;
  font-weight: 500;
  line-height: 160%;
  margin: 0;
}

.hero_title_store {
  color: var(--Red, #d64779);

  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  line-height: 100%; /* 20px */
}
@media (max-width: 720px) {
  .hero {
    flex-direction: column;
    align-items: center;
    height: 1000px;
  }

  .hero_img {
    max-height: 500px;
    margin-top: 20px;
  }

  .hero_title {
    flex-direction: column;
    align-items: center;
  }
  .hero_title h1 {
    text-align: center;
  }
}
</style>
