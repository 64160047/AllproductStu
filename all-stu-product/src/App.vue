<script setup>
import Navbar from './components/Navbar.vue';
import HeroSection from './components/HeroSection.vue';
import ProductList from './components/ProductList.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <Navbar />
  <main class="container">
    <HeroSection />
    <ProductList />
  </main>
  <Footer />
</template>

<style scoped>
/* ✅ ป้องกัน overflow และขยายเต็มหน้าจอ */
html, body {
  margin: 0;
  padding: 0;
  width: 100vw;
  height: 100%;
  overflow-x: hidden;
  box-sizing: border-box;
}

/* ✅ ป้องกัน scroll ด้านข้าง */
#app {
  max-width: 100vw;
  overflow-x: hidden;
}

/* ✅ แก้ให้ container กว้างเต็มหน้าจอ */
.container {
  display: flex;
  flex-direction: column;
  width: 100vw;  /* ✅ ปรับจาก 50vw → 100vw */
  min-height: 100vh; /* ✅ ให้มีความสูงเต็มจอ */

  margin: 0;
  padding: 0;
}

/* ✅ ลบช่องว่างที่ไม่จำเป็น */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
