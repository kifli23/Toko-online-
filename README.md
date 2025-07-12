# Toko-online-
tokoh-website/
├── index.html
├── style.css
└── assets/
    └── foto-tokoh.jpg   ← Kamu bisa ganti ini nanti
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Profil Tokoh – Kifli23</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kifli23</h1>
    <p>Tokoh | Profil Online</p>
  </header>

  <section id="about">
    <h2>Tentang Saya</h2>
    <img src="assets/foto-tokoh.jpg" alt="Foto Kifli23" class="profile">
    <p>Halo! Saya Kifli23, seorang [profesi/bidang] yang bersemangat berbagi ide dan inspirasi. Website ini adalah identitasku secara online – nyaman untuk kamu jelajahi.</p>
  </section>

  <section id="works">
    <h2>Karya & Aktivitas</h2>
    <ul>
      <li>Contoh karya: “Tulisan Inspiratif” (2025)</li>
      <li>Pembicara di: Webinar Edukasi Digital</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Kontak</h2>
    <p>Email: <a href="mailto:kifli23@example.com">kifli23@example.com</a></p>
    <p>Instagram: <a href="https://instagram.com/kifli23" target="_blank">@kifli23</a></p>
  </section>

  <footer>&copy; 2025 Kifli23</footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f0f0f0;
  color: #333;
}

header {
  background: #2c3e50;
  color: white;
  padding: 30px;
  text-align: center;
}

section {
  background: white;
  margin: 20px auto;
  padding: 20px;
  max-width: 800px;
  border-radius: 8px;
}

.profile {
  display: block;
  margin: 20px auto;
  width: 150px;
  border-radius: 50%;
}

footer {
  text-align: center;
  padding: 15px;
  background: #bdc3c7;
}
