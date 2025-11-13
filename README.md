<!doctype html>
<html lang="uz">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Men haqimda — Ismingiz</title>
  <style>
    :root{--bg:#f7f7fb;--card:#ffffff;--accent:#2563eb;--muted:#6b7280}
    *{box-sizing:border-box}
    body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:var(--bg); color:#111}
    .container{max-width:900px;margin:32px auto;padding:20px}
    .card{background:var(--card);border-radius:12px;padding:24px;box-shadow:0 6px 20px rgba(31,41,55,0.06)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:12px;overflow:hidden;flex:0 0 110px;background:linear-gradient(135deg,#e6eefc,#f3f6ff);display:grid;place-items:center;font-weight:700;color:var(--muted)}
    h1{margin:0;font-size:22px}
    p.lead{margin:8px 0 0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:18px}
    section{padding:12px}
    .section-title{font-weight:700;margin-bottom:8px}
    ul{margin:0;padding-left:18px}
    .contact a{display:inline-block;margin-right:8px;text-decoration:none;color:var(--accent)}
    .tag{display:inline-block;padding:6px 10px;border-radius:999px;background:#f1f5f9;margin:6px 6px 0 0;font-size:14px;color:#111}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:820px){.grid{grid-template-columns:1fr;}.avatar{width:88px;height:88px}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <header>
        <div class="avatar">Rasm</div>
        <div>
          <h1>Ismingiz Familiyangiz</h1>
          <p class="lead">Short bio — qisqacha: 20–30 so‘z bilan o‘zingizni tanishtiring (masalan: talabaman, web-dasturchi, grafik dizayner).</p>
          <div class="contact" style="margin-top:10px">
            <a href="#mailto" aria-label="Email">📧 email@misol.com</a>
            <a href="#tel" aria-label="Telefon">📱 +998 90 123 45 67</a>
          </div>
        </div>
      </header>

      <div class="grid">
        <main>
          <section>
            <div class="section-title">Men haqimda</div>
            <p>Siz haqingizda batafsil: qaysi sohada ishlaysiz yoki o‘qiysiz, qiziqishlaringiz, asosiy yutuqlaringiz va nima uchun bu ishni yaxshi ko‘rishingiz haqida 3–4 gap yozing.</p>
          </section>

          <section>
            <div class="section-title">Tajriba</div>
            <ul>
              <li><strong>Lavozim</strong> — Kompaniya / Maktab (2023 — hozir)</li>
              <li><strong>Lavozim</strong> — Kompaniya (2021 — 2022)</li>
            </ul>
          </section>

          <section>
            <div class="section-title">Ta'lim</div>
            <ul>
              <li>Universitet / Maktab — Mutaxassislik (2019 — 2023)</li>
            </ul>
          </section>

          <section>
            <div class="section-title">Loyihalar</div>
            <p>Qisqacha — asosiy loyihalaringiz, GitHub havolalari yoki portfolio linklarini keltiring.</p>
          </section>
        </main>

        <aside>
          <section>
            <div class="section-title">Ko'nikmalar</div>
            <div>
              <span class="tag">HTML</span>
              <span class="tag">CSS</span>
              <span class="tag">JavaScript</span>
              <span class="tag">Figma</span>
            </div>
          </section>

          <section>
            <div class="section-title">Til</div>
            <ul>
              <li>O‘zbekcha — Ona tili</li>
              <li>Ruscha — O‘rta</li>
              <li>Inglizcha — Boshlang‘ich / O‘rta</li>
            </ul>
          </section>

          <section>
            <div class="section-title">Bog'lanish</div>
            <p>Manzil (shahar): Tashkent</p>
            <p>Email: email@misol.com</p>
            <p>Telegram: @username</p>
          </section>
        </aside>
      </div>

      <footer>
        © <span id="year"></span> Ismingiz. Barcha huquqlar himoyalangan.
      </footer>
    </div>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
