<template>
  <div class="header">
    <div>
      <img src="../assets/Logo.png" alt="Logo" />
    </div>
    <div>
      <nav class="header_nav">
        <a class="header_nav-a" href="#">Home</a>
        <a class="header_nav-a" href="#">About Us</a>
        <a class="header_nav-a" href="#">Products</a>
        <a class="header_nav-a" href="#">Services</a>
        <a class="header_nav-a" href="#">Pricing</a>
        <a class="header_nav-a" href="#">Contact Us</a>
      </nav>
    </div>
    <div class="headerBtnContact">
      <span>+62 864 6444 2222</span>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="8"
        viewBox="0 0 16 8"
        fill="none"
      >
        <path
          d="M15.3536 4.35355C15.5488 4.15829 15.5488 3.84171 15.3536 3.64645L12.1716 0.464466C11.9763 0.269204 11.6597 0.269204 11.4645 0.464466C11.2692 0.659728 11.2692 0.976311 11.4645 1.17157L14.2929 4L11.4645 6.82843C11.2692 7.02369 11.2692 7.34027 11.4645 7.53553C11.6597 7.7308 11.9763 7.7308 12.1716 7.53553L15.3536 4.35355ZM0 4.5H15V3.5H0V4.5Z"
          fill="white"
        />
      </svg>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background: #dee9ff;
  padding-top: 60px;
}

.headerBtnContact {
  color: var(--White, #fff);
  display: inline-flex;
  padding: 12px 22px;
  align-items: center;
  gap: 6px;
  border-radius: 100px;
  background: var(--Accent, #1364ff);
}

.header_nav {
  display: inline-flex;
  align-items: flex-start;
  gap: 24px;
}

.header_nav-a {
  text-decoration: none;
  color: black;
}

.header_nav-a:hover {
  background-color: #1364ff;
  border-radius: 5px;
  color: white;
}

@media (max-width: 720px) {
  .header {
    flex-direction: column;
  }

  .header_nav {
    margin: 30px;
  }
}

@media (max-width: 480px) {
  .header {
    flex-direction: column;
  }

  .header_nav {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 30px 0px;
  }

  .header img {
    margin-top: 10px;
  }
}
</style>
