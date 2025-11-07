# 11b-Angiin-dursamj-
<!doctype html>
<html lang="mn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Анги - Дурсамж</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <h1>11Б ангийн дурсамж</h1>
      <p class="tagline">Бидний он цагийн хамгийн сайхан мөчүүд</p>
    </div>
  </header>

  <main class="wrap">
    <section id="about" class="card">
      <h2>Бидний тухай</h2>
      <p>Бид 11Б анги — сургууль, аялал, баяр ёслол, спортын олон сайхан дурсамжтай. Энэ сайтанд зургаас эхлээд тайлбар, огноо зэргийг байрлуулав.</p>
    </section>

    <section id="gallery" class="card">
      <h2>Зургийн цомог</h2>
      <div class="grid" id="galleryGrid">
        <!-- Доор жишээ зургууд байрлана. images хавтас руу өөрийн зургуудаа байрлуулна -->
        <figure class="thumb">
          <img src="images/2025-05-10_tengis.jpg" alt="Тэнгис аялал">
          <figcaption>
            <strong>Тэнгис аялал</strong><br>
            2025-05-10 — Бидний анхны аялал
          </figcaption>
        </figure>

        <figure class="thumb">
          <img src="images/2025-06-20_tugsult.jpg" alt="Төгсөлт">
          <figcaption>
            <strong>Төгсөлтийн өдөр</strong><br>
            2025-06-20 — Баяр жаргал
          </figcaption>
        </figure>

        <!-- Ижил загвараар өөр зургуудаа нэмнэ -->
      </div>
    </section>

    <section id="contact" class="card">
      <h2>Холбоо</h2>
      <p>Зураг эсвэл сэтгэгдэл илгээх: <a href="mailto:angi11b@example.com">angi11b@example.com</a></p>
    </section>
  </main>

  <!-- Lightbox -->
  <div id="lightbox" class="lightbox" aria-hidden="true">
    <button class="close" id="lbClose" aria-label="Хаах">&times;</button>
    <img id="lbImage" src="" alt="">
    <div id="lbCaption" class="lb-caption"></div>
  </div>

  <footer class="site-footer">
    <div class="wrap">
      <small>© Анги 11Б — Дурсамж • Бүх эрх хуулиар хамгаалагдсан</small>
    </div>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
