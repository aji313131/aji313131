i## Hi there 👋>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Profil Mahasiswa</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Halo, saya Aji</h1>
    <p>Mahasiswa Teknik Informatika</p>
    <nav>
      <a href="index.html">Beranda</a>
      <a href="tugas.html">Tugas</a>
      <a href="cv.pdf" download>Download CV</a>
      <button onclick="toggleDarkMode()">🌓</button>
    </nav>
  </header>

  <main>
    <img src="https://via.placeholder.com/120" alt="Foto Profil">
    <h2>Tentang Saya</h2>
    <p>Saya adalah mahasiswa aktif yang tertarik pada pengembangan web dan desain UI/UX.</p>
  </main>

  <footer>
    &copy; 2025 Aji313131
  </footer>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle("dark");
    }
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tugas Kuliah</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Daftar Tugas Kuliah</h1>
    <nav>
      <a href="index.html">Beranda</a>
      <a href="tugas.html">Tugas</a>
      <a href="cv.pdf" download>Download CV</a>
      <button onclick="toggleDarkMode()">🌓</button>
    </nav>
  </header>

  <main>
    <ul>
      <li>Makalah Sistem Informasi</li>
      <li>Website UKM Mahasiswa</li>
      <li>Riset UX Aplikasi Kampus</li>
    </ul>
  </main>

  <footer>
    &copy; 2025 Aji313131
  </footer>

  <s    function toggleDarkMode() {
      document.body.classList.toggle("dark")
    }
  </script>
</body>body>
</html>
body {
  font-family: sans-serif;
  margin: 0;
  background: #f7f7f7;
  color: #111;
  transition: 0.3s;
}
header {
  background: #004aad;
  color: white;
  padding: 20px;
  text-align: center;
}
nav {
  margin-top: 10px;
}
nav a, nav button {
  color: white;
  margin: 0 10px;
  text-decoration: none;
  background: none;
  border: none;
  cursor: pointer;
  font-weight: bold;
}
main {
  padding: 20px;
  max-width: 800px;
  margin: auto;
}
footer {
  text-align: center;
  padding: 20px;
  background: #ddd;
}

img {
  border-radius: 50%;
  display: block;
  margin: 20px auto;
}

body.dark {
  background: #121212;
  color: #eee;
}
body.dark header {
  background: #222;
}
body.dark footer {
  background: #1a1a1a;
}
body.dark nav a, body.dark nav button {
  color: #00bcd4;
}
