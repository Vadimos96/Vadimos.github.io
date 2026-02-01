<html lang="ru">
  title: 'py-build-cmake
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Свадебное приглашение</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">

  <!-- AOS CSS -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">

  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      overflow-x: hidden;
      background: #f3e7dc;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      color: #2b2b2b;
      text-align: center;
    }

    section {
      padding: 40px 20px;
      text-align: center;
    }

    h1, h2 {
      font-family: 'Playfair Display', serif;
      font-weight: 600;
      letter-spacing: 1px;
      text-align: center;
      margin: 0;
    }

    .content {
      max-width: 420px;
      width: calc(100% - 40px);
      margin: 0 auto;
      text-align: center;
    }

    .date {
      font-size: 24px;
      margin: 20px 0;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #ffffff;
      color: #2b2b2b;
      border-radius: 25px;
      text-decoration: none;
      margin-top: 20px;
    }

    /* ===== HERO ===== */
    .hero {
      position: relative;
      width: 100vw;
      height: 100vh;
      min-height: 560px;
      background-image: url('https://i.ibb.co/tNqhjRJ/0dbdc028f90d6278b7d1382faeb8088f.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .hero::after {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(
        to bottom,
        rgba(0,0,0,0.5) 0%,
        rgba(0,0,0,0.25) 40%,
        rgba(0,0,0,0) 70%
      );
      z-index: 1;
    }

    .names {
      position: absolute;
      top: 370px;   
      left: 46%;    
      transform: translateX(-50%);
      max-width: 420px;
      width: calc(100% - 40px);
      text-align: center;
      color: #ffffff;
      font-size: 44px;
      line-height: 1.2;
      font-family: 'Playfair Display', serif;
      z-index: 2;
    }

    /* ===== МЫ ===== */
    .about-us {
      position: relative;
      width: 100vw;
      min-height: 650px; /* увеличено на 30% */
      background-image: url('https://i.ibb.co/Q3dFxJdK/c7436a2d5a513fdd61f262447b1cf2cb.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #ffffff;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .about-us h2 {
      font-size: 40px;
      z-index: 2;
    }

    /* ===== LOCATION ===== */
    .location {
      position: relative;
      width: 100vw;
      min-height: 700px;
      background-image: url('https://i.ibb.co/VkJ1mMm/4293d97751ef1b8673e68a3fb7a4369f-1.png');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #ffffff;
    }

    .location::before {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(
        to bottom,
        rgba(0,0,0,0) 0%,
        rgba(0,0,0,0.35) 45%,
        rgba(0,0,0,0.35) 55%,
        rgba(0,0,0,0) 100%
      );
      z-index: 1;
    }

    .location .content {
      position: absolute;
      top: 370px;
      left: 46%;
      transform: translateX(-50%);
      z-index: 2;
      max-width: 420px;
      width: calc(100% - 40px);
      text-align: center;
    }

    /* ===== ТАЙМИНГ ===== */
    .timing {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .time-row {
      display: flex;
      justify-content: space-between;
      width: 100%;
      max-width: 420px;
      margin: 10px 0;
      border-bottom: 1px solid #d8cfc6;
      padding-bottom: 10px;
      text-align: center;
    }

    /* ===== DRESS CODE ===== */
    .dress-code .colors {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 10px;
    }

    .dress-code span {
      display: inline-block;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      border: 1px solid #000;
    }

    .sage   { background: #cce4c4; }
    .mint   { background: #b4dcb4; }
    .olive  { background: #97bb9e; }
    .forest { background: #7ca48c; }

    /* Текст после дресс-кода */
    .note {
      max-width: 420px;
      width: calc(100% - 40px);
      margin: 0 auto 60px auto;
      text-align: center;
      font-size: 16px;
      line-height: 1.5;
      color: #2b2b2b;
    }

    footer {
      padding: 30px;
      font-size: 12px;
      opacity: 0.7;
      text-align: center;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
    <div class="names">ВАДИМ<br>&amp;<br>АЛСУ</div>
  </section>

  <section data-aos="fade-up">
    <div class="content">
      <p><strong>ДОРОГИЕ ДРУЗЬЯ И РОДНЫЕ!</strong></p>
      <p>Есть события которые остаются в памяти на всю жизнь.<br>
         Есть люди, с которыми хочется их разделить.<br>
         С большой радостью приглашаем вас разделить с нами главное событие этой весны - день нашей свадьбы.</p>
      <div class="date">18.04.26</div>
      <p>Просим подтвердить присутствие, заполнив форму ниже</p>
      <a href="#" class="btn">Заполнить форму гостя</a>
    </div>
  </section>

  <!-- МЫ -->
  <section class="about-us" data-aos="fade-up">
    <h2>МЫ</h2>
  </section>

  <!-- ТАЙМИНГ -->
  <section data-aos="fade-up">
    <div class="content timing">
      <h2>Тайминг</h2>
      <div class="time-row" data-aos="fade-right"><span>16:30</span><span>Сбор гостей / фуршет</span></div>
      <div class="time-row" data-aos="fade-right" data-aos-delay="100"><span>17:00</span><span>Торжественная церемония</span></div>
      <div class="time-row" data-aos="fade-right" data-aos-delay="200"><span>17:30</span><span>Праздничный ужин</span></div>
      <div class="time-row" data-aos="fade-right" data-aos-delay="300"><span>23:00</span><span>Завершение банкета</span></div>
    </div>
  </section>

  <!-- LOCATION -->
  <section class="location" data-aos="fade-up">
    <div class="content">
      <h2>ЛОКАЦИЯ</h2>
      <p>Место проведения</p>
      <p><strong>Комплекс «Тан»<br>г. Уфа, ул. Рихарда Зорге, 65</strong></p>
      <a href="#" class="btn">Посмотреть на карте</a>
    </div>
  </section>

  <!-- ДРЕСС-КОД -->
  <section data-aos="fade-up">
    <div class="content dress-code">
      <h2>ДРЕСС-КОД</h2>
      <p>Для нас самое главное - ваше присутствие</p>
      <p>Но мы будем очень благодарны, если поддержите цветовую гамму нашей свадьбы</p>
      <div class="colors">
        <span class="sage"></span>
        <span class="mint"></span>
        <span class="olive"></span>
        <span class="forest"></span>
      </div>
    </div>
  </section>

  <!-- NOTE ABOUT CHILDREN -->
  <section data-aos="fade-up">
    <div class="note">
      Просим оставить ваших малышей в надежных руках на день торжества, так как формат нашей свадьбы не предполагает детской зоны и аниматоров.
    </div>
  </section>

  <footer>
    С любовью, Вадим & Алсу
  </footer>

  <!-- AOS JS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  <script>
    AOS.init({
      duration: 1200,
      once: true
    });
  </script>
</body>
</html>
