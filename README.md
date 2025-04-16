# Portofolio
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Baso Ruswan Aldi - Portofolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f8fb;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #007acc, #005b99);
      color: white;
      padding: 3rem 2rem;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    header img {
      width: 150px;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 1rem;
      border: 3px solid white;
    }
    header h1 {
      font-size: 2.5rem;
      margin: 0.5rem 0;
    }
    header p {
      font-size: 1.1rem;
      margin: 0;
    }
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #005b99;
      margin-bottom: 1rem;
      border-bottom: 2px solid #e0e0e0;
      padding-bottom: 0.5rem;
    }
    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .projects div, .skills div {
      background: white;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }
    footer {
      background: #005b99;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      font-size: 0.9rem;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="baso-ruswan-aldi.jpg" alt="Baso Ruswan Aldi">
    <h1>Baso Ruswan Aldi</h1>
    <p>Lulusan Perencanaan Wilayah & Kota | GIS & Mapping | AutoCAD & RAB</p>
  </header>

  <section>
    <h2>Tentang Saya</h2>
    <p>Saya adalah lulusan S1 Perencanaan Wilayah dan Kota dengan pengalaman dalam pemetaan, penyusunan tata ruang, dan konstruksi. Memiliki keterampilan dalam pengolahan data spasial menggunakan GIS serta penguasaan AutoCAD dan estimasi anggaran proyek. Berpengalaman dalam penyusunan RDTR, survei lapangan, serta ilustrasi grafis kawasan berbasis transek.</p>
  </section>

  <section>
    <h2>Keahlian</h2>
    <div class="skills">
      <div>
        <strong>GIS & Pemetaan</strong>
        <p>ArcMap, pembuatan peta tematik, analisis data spasial.</p>
      </div>
      <div>
        <strong>Desain Grafis</strong>
        <p>Adobe Illustrator, ilustrasi kawasan, visualisasi data.</p>
      </div>
      <div>
        <strong>Konstruksi</strong>
        <p>AutoCAD, pembuatan DED, perhitungan RAB menggunakan AHSP.</p>
      </div>
      <div>
        <strong>Bahasa</strong>
        <p>Indonesia (aktif), English (menengah).</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Proyek</h2>
    <div class="projects">
      <div>
        <h3>RDTR Kawasan Industri Tolala</h3>
        <p>Magang di PT Angkasa Global Consultant, terlibat dalam penyusunan dokumen Rencana Detail Tata Ruang kawasan industri di Tolala.</p>
      </div>
      <div>
        <h3>Analisis Transek Perkotaan Maros</h3>
        <p>Melakukan observasi dan klasifikasi karakteristik kawasan berdasarkan garis transek; menghasilkan ilustrasi visual kawasan menggunakan Adobe Illustrator.</p>
      </div>
      <div>
        <h3>Perencanaan Rumah & RAB</h3>
        <p>Membuat gambar kerja rumah sederhana dan menghitung anggaran biaya konstruksi berdasarkan DED dan AHSP.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Kontak</h2>
    <p>Email: <a href="mailto:aldibasoruswan@gmail.com">aldibasoruswan@gmail.com</a><br />
    Telepon: +62 821-9878-7195<br />
    Lokasi: Makassar, Indonesia</p>
  </section>

  <footer>
    &copy; 2025 Baso Ruswan Aldi. All rights reserved.
  </footer>
</body>
</html>
