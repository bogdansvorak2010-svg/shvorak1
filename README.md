<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GameNews</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
    }

    header {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #444;
    }

    header h1 {
      margin: 0;
      color: #00bfff;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .news-card {
      background: #1c1c1c;
      border-radius: 12px;
      overflow: hidden;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    .news-card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .news-content {
      padding: 15px;
    }

    .news-content h2 {
      margin-top: 0;
      color: #00bfff;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1e1e1e;
      margin-top: 30px;
      border-top: 2px solid #444;
    }

    @media (max-width: 600px) {
      .news-card img {
        height: 180px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🎮 GameNews</h1>
    <nav>
      <a href="#">Головна</a>
      <a href="#">Новини</a>
      <a href="#">Ігри</a>
      <a href="#">Контакти</a>
    </nav>
  </header>

  <div class="container">

    <div class="news-card">
      <img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1200&auto=format&fit=crop" alt="Gaming News">
      <div class="news-content">
        <h2>Новий трейлер GTA 6</h2>
        <p>Rockstar Games показала новий трейлер GTA 6. Гравців чекає величезний відкритий світ і покращена графіка.</p>
      </div>
    </div>

    <div class="news-card">
      <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1200&auto=format&fit=crop" alt="Cyberpunk">
      <div class="news-content">
        <h2>Cyberpunk 2077 отримує оновлення</h2>
        <p>CD Projekt RED випустила нове оновлення з покращенням продуктивності та виправленням багів.</p>
      </div>
    </div>

    <div class="news-card">
      <img src="https://images.unsplash.com/photo-1493711662062-fa541adb3fc8?q=80&w=1200&auto=format&fit=crop" alt="Metro">
      <div class="news-content">
        <h2>Чутки про нову частину Metro</h2>
        <p>З'явилися чутки, що нова гра серії Metro знаходиться в активній розробці.</p>
      </div>
    </div>

  </div>

  <footer>
    <p>© 2026 GameNews | Зроблено Богданом</p>
  </footer>

</body>
</html>
