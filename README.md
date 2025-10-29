<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mert ÇELİK GitHub Mockup</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #111;
  }

  header {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }

  header img {
    width: 70px;
    height: 70px;
    border-radius: 50%;
    border: 2px solid #007aff;
    margin-right: 20px;
  }

  header div h1 {
    margin: 0;
    font-size: 1.8rem;
    color: #007aff;
  }

  header div p {
    margin: 5px 0 0 0;
    color: #555;
  }

  main {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
  }

  .repo {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .repo:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  }

  .repo h2 {
    margin-top: 0;
    color: #007aff;
  }

  .repo p {
    color: #333;
  }

  .tags {
    margin-top: 10px;
  }

  .tag {
    display: inline-block;
    background-color: #e0eaff;
    color: #007aff;
    padding: 3px 8px;
    border-radius: 5px;
    margin-right: 5px;
    font-size: 0.8rem;
  }
</style>
</head>
<body>

<header>
  <img src="https://avatars.githubusercontent.com/u/000000?v=4" alt="Profil Fotoğrafı">
  <div>
    <h1>Mert ÇELİK</h1>
    <p>Python & Flutter Developer</p>
  </div>
</header>

<main>
  <div class="repo">
    <h2>Chat Metin Programı</h2>
    <p>Python ile geliştirdiğim metin işleme uygulaması.</p>
    <div class="tags">
      <span class="tag">Python</span>
      <span class="tag">OOP</span>
    </div>
  </div>

  <div class="repo">
    <h2>Mobil Uygulama</h2>
    <p>Flutter ile geliştirdiğim cross-platform mobil uygulama.</p>
    <div class="tags">
      <span class="tag">Flutter</span>
      <span class="tag">Dart</span>
    </div>
  </div>

  <div class="repo">
    <h2>Veritabanı Projesi</h2>
    <p>SQL ve MySQL kullanarak geliştirdiğim veri tabanı uygulaması.</p>
    <div class="tags">
      <span class="tag">SQL</span>
      <span class="tag">MySQL</span>
    </div>
  </div>
</main>

</body>
</html>
