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
      background-color: #111;
      color: white;
    }

    header {
      background-color: #1e1e1e;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #333;
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
      font-size: 18px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .news-card {
      background-color: #1c1c1c;
      border-radius: 12px;
      overflow: hidden;
      margin-bottom: 25px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    .news-card img {
      width: 100%;
      height: 260px;
      object-fit: cover;
    }

    .news-content {
      padding: 20px;
    }

    .news-content h2 {
      margin-top: 0;
      color: #00bfff;
    }

    .news-content p {
      line-height: 1.6;
      font-size: 17px;
    }

    footer {
      background-color: #1e1e1e;
      text-align: center;
      padding: 20px;
      border-top: 2px solid #333;
      margin-top: 30px;
    }

    @media (max-width: 700px) {
      .news-card img {
        height: 180px;
      }

      nav a {
        display: inline-block;
        margin: 5px;
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
      <img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1200&auto=format&fit=crop" alt="GTA 6">

      <div class="news-content">
        <h2>Новий трейлер GTA 6</h2>

        <p>
          Rockstar Games офіційно показала новий трейлер GTA 6.
          У відео продемонстрували величезне сучасне місто,
          нових персонажів та значно покращену графіку.
          Гра отримає деталізований відкритий світ,
          реалістичну фізику автомобілів та оновлену систему взаємодії з NPC.
          Багато гравців уже називають GTA 6 найочікуванішою грою останніх років.
        </p>
      </div>
    </div>

    <div class="news-card">
      <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1200&auto=format&fit=crop" alt="Cyberpunk 2077">

      <div class="news-content">
        <h2>Cyberpunk 2077 отримала нове оновлення</h2>

        <p>
          Компанія CD Projekt RED випустила велике оновлення для Cyberpunk 2077.
          Розробники покращили продуктивність гри,
          виправили помилки та додали нові можливості.
          Також було оновлено поведінку ворогів,
          транспорт та стабільність гри на комп'ютерах і консолях.
          Оновлення вже доступне для всіх гравців.
        </p>
      </div>
    </div>

    <div class="news-card">
      <img src="https://images.unsplash.com/photo-1493711662062-fa541adb3fc8?q=80&w=1200&auto=format&fit=crop" alt="Metro">

      <div class="news-content">
        <h2>Чутки про нову частину Metro</h2>

        <p>
          У мережі активно обговорюють нову гру серії Metro.
          За чутками, розробники працюють над ще більш атмосферним
          постапокаліптичним світом із сучасною графікою.
          Очікуються нові механіки виживання,
          розширений сюжет та великі відкриті локації.
          Офіційного анонсу поки що немає,
          але фанати серії з нетерпінням чекають новин.
        </p>
      </div>
    </div>

  </div>

  <footer>
    <p>© 2026 GameNews | Зроблено Богданом</p>
  </footer>

</body>
</html>
