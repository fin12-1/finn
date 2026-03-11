<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>CV ALFIN RAMADHAN</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background: #ddd;
    }

    .cv {
      max-width: 1000px;
      margin: auto;
      background: #fff;
      display: grid;
      grid-template-columns: 320px 1fr;
      min-height: 100vh;
    }

    /* ===== HEADER ===== */
    .header {
      grid-column: 1 / -1;
      background: #3e4147;
      color: white;
      padding: 30px;
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .photo img {
      width: 90px;
      height: 90px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid white;
    }

    .header h1 {
      margin: 0;
      font-size: 28px;
    }

    .header p {
      margin: 5px 0 0;
      font-size: 16px;
      opacity: 0.9;
    }

    /* ===== SIDEBAR ===== */
    .sidebar {
      background: #f1ece6;
      padding: 30px;
    }

    .sidebar h3 {
      margin-top: 0;
      border-bottom: 2px solid #555;
      padding-bottom: 5px;
      font-size: 18px;
    }

    .sidebar p,
    .sidebar li {
      font-size: 14px;
      color: #333;
    }

    .sidebar ul {
      padding-left: 18px;
    }

    /* ===== MAIN CONTENT ===== */
    .content {
      padding: 30px;
    }

    .content h2 {
      margin-top: 0;
      border-bottom: 2px solid #000;
      padding-bottom: 5px;
      font-size: 20px;
    }

    .content p {
      font-size: 14px;
      line-height: 1.6;
      color: #333;
    }

    .content ul {
      padding-left: 18px;
      font-size: 14px;
    }

    .job {
      margin-bottom: 20px;
    }

    .job strong {
      display: block;
      font-size: 15px;
    }

    .job span {
      font-size: 13px;
      color: #666;
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 768px) {
      .cv {
        grid-template-columns: 1fr;
      }

      .header {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>

<body>

<div class="cv">

  <!-- HEADER -->
  <div class="header">
    <div class="photo">
      <!-- Ganti foto.jpg dengan foto kamu -->
      <img src="dndi.jfif">
    </div>
    <div>
      <h1>ALFIN RAMADHAN</h1>
      <p>Siswa SMKN 1 RANGKASBITUNG – Teknik Jaringan Komputer dan Telekomunikasi</p>
    </div>
  </div>

  <!-- SIDEBAR -->
  <aside class="sidebar">
    <h3>Detail Kontak</h3>
    <p>📧 ALFINTJKT@email.com</p>
    <p>📞 0895320737400</p>
    <p>📍 Rangkasbitung Lebak Banten</p>

    <h3>Pendidikan</h3>
    <ul>
      <li>
        <strong>SMKN 1 RANGKASBITUNG</strong><br>
        Teknik Komputer dan Jaringan<br>
        Tahun Ajaran 2025/2026
      </li>
    </ul>

    <h3>Keterampilan</h3>
    <ul>
      <li>Networking Dasar</li>
      <li>Microsoft Office</li>
      <li>HTML & CSS Dasar</li>
      <li>Administrasi</li>
    </ul>
  </aside>

  <!-- MAIN CONTENT -->
  <main class="content">
    <h2>Ringkasan</h2>
    <p>
      Siswa SMKN 1 RANGKASBITUNG jurusan Teknik Komputer dan Jaringan yang memiliki minat di
      bidang IT dan jaringan komputer. Terbiasa bekerja secara rapi,
      disiplin, dan bertanggung jawab.
    </p>

    <h2>Pengalaman Kerja</h2>

    <div class="job">
      <strong>PKL – Diskominfo</strong>
      <span>Juli 2024 – November 2024</span>
      <ul>
        <li>Membantu pengelolaan dan dokumentasi administrasi.</li>
        <li>Konfigurasi jaringan dasar menggunakan Cisco Packet Tracer.</li>
        <li>Mendukung kegiatan operasional lapangan.</li>
      </ul>
    </div>

    <
  </main>

</div>

</body>
</html>
