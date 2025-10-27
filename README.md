<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kodhan | İletişim</title>
  <style>
    /* ==============================
   İLETİŞİM SAYFASI
============================== */
.contact {
  background: #fff;
  padding: 80px 60px;
  text-align: center;
}

.contact h2 {
  font-size: 36px;
  color: #111;
  margin-bottom: 10px;
}

.contact .subtitle {
  color: #666;
  font-size: 16px;
  margin-bottom: 50px;
}

.contact-content {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  gap: 50px;
  flex-wrap: wrap;
}

.contact-info {
  flex: 1;
  min-width: 300px;
  text-align: left;
  background: #f9f9f9;
  border-radius: 12px;
  padding: 30px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.contact-info h3 {
  color: #00bfff;
  margin-bottom: 20px;
}

.contact-info p {
  margin-bottom: 10px;
  color: #333;
}

/* Form */
.contact-form {
  flex: 1;
  min-width: 320px;
  background: #f9f9f9;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 15px;
  outline: none;
  transition: 0.3s;
}

.contact-form input:focus,
.contact-form textarea:focus {
  border-color: #00bfff;
}

.contact-form button {
  background: #00bfff;
  color: white;
  border: none;
  padding: 12px 25px;
  border-radius: 8px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
  width: 100%;
}

.contact-form button:hover {
  background: #0099cc;
}

  </style>
</head>
<body>

  <!-- Üst Menü -->
    <header>
        <div class="logo">KODHAN</div>
            <nav>
                <a href="index.html">Anasayfa</a>
                <a href="hakımızda.htm">Hakkımızda</a>
                <a href="hizmeyler.html">Hizmetler</a>
                <a href="iletiasim.html">İletişim</a>
                <a href="login.html" class="login-btn">Giriş</a>
            </nav>
    </header>

  <!-- İletişim Bölümü -->
  <section class="contact" id="contact">
    <div class="contact-container">
      <h2>Bizimle İletişime Geçin</h2>
      <p class="subtitle">Sorularınız, önerileriniz veya projeleriniz için bizimle bağlantıya geçin.</p>

      <div class="contact-content">
        <!-- Sol Kısım (İletişim Bilgileri) -->
        <div class="contact-info">
          <h3>İletişim Bilgileri</h3>
          <p><strong>Adres:</strong> Karasu, sakarya</p>
          <br>
          <p><strong>E-posta:</strong> hakanakdogan019840@gmail.com</p>
          <br>
          <p><strong>Telefon:</strong> +90 530 798 84 94</p>
          <br>
          <p><strong>Çalışma Saatleri:</strong> Hafta içi 11:00 - 17:20</p>
        </div>

      </div>
    </div>
  </section>

  <footer id="contact">
    <h2>İletişim</h2>
    <p>Email: <a href="mailto:hakanakdogan019840@gmail.com">hakanakdogan019840@gmail.com</a></p>
    <p>© 2025 Kodhan Yazılım | Tüm Hakları Saklıdır</p>
  </footer>

  <script src="/css.js/app.js"></script>
</body>
</html>
