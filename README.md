<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profilim</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #111;
      padding: 20px;
    }

    header {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-bottom: 40px;
    }

    header img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #007aff;
    }

    header h1 {
      font-size: 2rem;
      font-weight: 600;
    }

    header p {
      font-size: 1rem;
      color: #555;
    }

    .repo-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .repo-card {
      background-color: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .repo-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }

    .repo-card h2 {
      font-size: 1.2rem;
      margin-bottom: 10px;
      color: #007aff;
    }

    .repo-card p {
      font-size: 0.95rem;
      color: #333;
      margin-bottom: 10px;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 5px;
    }

    .tag {
      background-color: #e0eaff;
      color: #007aff;
      padding: 3px 8px;
      border-radius: 6px;
      font-size: 0.8rem;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://avatars.githubusercontent.com/u/000000?v=4" alt="Profil Fotoğrafı">
    <div>
      <h1>Mert ÇELİK</h1>
      <p>Fullstack Developer | Python & Flutter</p>
    </div>
  </header>

  <section class="repo-grid">
    <div class="repo-card">
      <h2>Chat Metin Programı</h2>
      <p>Python ile geliştirdiğim metin işleme uygulaması.</p>
      <div class="tags">
        <span class="tag">Python</span>
        <span class="tag">OOP</span>
      </div>
    </div>

    <div class="repo-card">
      <h2>Mobil Uygulama</h2>
      <p>Flutter ile geliştirdiğim cross-platform mobil uygulama.</p>
      <div class="tags">
        <span class="tag">Flutter</span>
        <span class="tag">Dart</span>
      </div>
    </div>

    <div class="repo-card">
      <h2>Veritabanı Projesi</h2>
      <p>SQL ve MySQL kullanarak geliştirdiğim veri tabanı uygulaması.</p>
      <div class="tags">
        <span class="tag">SQL</span>
        <span class="tag">MySQL</span>
      </div>
    </div>
  </section>

</body>
</html>
