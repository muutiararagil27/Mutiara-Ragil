<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Grafika Komputer - Larisa</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f3ef;
      color: #4e342e;
    }

    header {
      background: linear-gradient(135deg, #8d6e63, #a1887f);
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    nav {
      background-color: #d7ccc8;
      padding: 10px 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 40px;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      text-decoration: none;
      color: #4e342e;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #3e2723;
    }

    section {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }

    .kartu {
      background-color: #efebe9;
      border-radius: 12px;
      padding: 25px;
      margin-bottom: 25px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.2s;
    }

    .kartu:hover {
      transform: translateY(-5px);
    }

    .kartu h2 {
      margin-top: 0;
      color: #5d4037;
    }

    .kartu ul {
      padding-left: 20px;
    }

    .kartu ul li {
      margin-bottom: 10px;
    }

    .profil-list {
      list-style: none;
      padding-left: 0;
    }

    .profil-list li {
      margin-bottom: 8px;
    }

    .foto-profil {
      display: block;
      margin: 0 auto 20px auto;
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #6d4c41;
      color: white;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Grafika Komputer</h1>
    <p>Larisa Ramadhanty</p>
  </header>

  <nav>
    <ul>
      <li><a href="#profil">Profil</a></li>
      <li><a href="#tentang">Tentang</a></li>
    </ul>
  </nav>

  <section>
    <div class="kartu">
      <h2>Tugas 1: Garis DDA</h2>
      <ul>
        <li><a href="https://drive.google.com/file/d/1c4JUQ6K8ZUu7fcrzBGT4NKU0ocVtfMlI/view?usp=drivesdk" target="_blank">Tonton Video</a></li>
      </ul>
    </div>

    <div class="kartu">
      <h2>Tugas 2: Garis Lingkaran</h2>
      <ul>
        <li><a href="https://drive.google.com/file/d/1jtm9s2mWtJbqWVHXzk6Sv36cZsZTz51y/view?usp=drivesdk" target="_blank">Tonton Video</a></li>
      </ul>
    </div>

    <div class="kartu" id="profil">
      <h2>Profil</h2>
      <img src="larisa.jpg" alt="Foto Larisa Ramadhanty" class="foto-profil">
      <ul class="profil-list">
        <li><strong>Nama:</strong> Larisa Ramadhanty</li>
        <li><strong>NIM:</strong> 2413025065</li>
        <li><strong>Program Studi:</strong> Pendidikan Teknologi Informasi</li>
        <li><strong>Fakultas:</strong> FKIP</li>
        <li><strong>Universitas:</strong> Universitas Lampung</li>
        <li><strong>Email:</strong> larisaramadhanty12@gmail.com</li>
        <li><strong>Domisili:</strong> Bandar Lampung, Indonesia</li>
      </ul>
    </div>

    <div class="kartu" id="tentang">
      <h2>Tentang Saya</h2>
      <p>Halo! Saya <strong>Larisa Ramadhanty</strong>, mahasiswa semester 2 di Universitas Lampung, jurusan Pendidikan Teknologi Informasi.</p>
      <p>Saat ini saya sedang menempuh pendidikan S1 dan fokus belajar tentang penerapan teknologi dalam dunia pendidikan. Salah satu materinya adalah algoritma grafika seperti garis DDA dan lingkaran, yang saya pelajari dalam mata kuliah Grafika Komputer.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Larisa Ramadhanty</p>
  </footer>

</body>
</html>
