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

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle("dark");
    }
  </script>
</body>
</html>
