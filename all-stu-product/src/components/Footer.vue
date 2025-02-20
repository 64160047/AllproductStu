<template>
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-section">
          <h4>Contact us</h4>
          <p>xxxxxxxxx</p>
          <p>xxxxxxxxx</p>
        </div>
        <div class="footer-section">
          <h4>Information</h4>
          <p>xxxxxxxxx</p>
          <p>xxxxxxxxx</p>
        </div>
        <div class="footer-logo">
          <h4>Speech and Text Understanding Research Team (STU)</h4>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped>
  /* ✅ Footer เต็มจอ ไม่มีช่องว่าง */
  .footer {
    width: 100vw;
    background: linear-gradient(to right, #000000, #2a0a4a);
    color: white;
    padding: 30px 5%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  /* ✅ ปรับโครงสร้างให้อ่านง่าย */
  .footer-content {
    display: flex;
    width: 100%;
    max-width: 1200px;
    justify-content: space-between;
  }
  
  /* ✅ Style สำหรับแต่ละ section */
  .footer-section {
    text-align: left;
  }
  
  .footer-section h4 {
    font-size: 16px;
    font-weight: bold;
  }
  
  .footer-section p {
    font-size: 14px;
    color: #d1d5db;
  }
  
  /* ✅ ส่วนของโลโก้ */
  .footer-logo {
    text-align: right;
    font-size: 16px;
    font-weight: bold;
  }
  
  /* ✅ ปรับให้ responsive */
  @media (max-width: 768px) {
    .footer-content {
      flex-direction: column;
      text-align: center;
    }
  
    .footer-logo {
      text-align: center;
      margin-top: 15px;
    }
  }
  </style>
  