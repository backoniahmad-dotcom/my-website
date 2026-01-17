<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي الشخصي</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #F9FAFB;
      color: #1E3A8A;
    }
    header {
      background-color: #1E3A8A;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: #FBBF24;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    .btn {
      background-color: #FBBF24;
      color: #1E3A8A;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    .card {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin: 20px auto;
      max-width: 400px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #1E3A8A;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>مرحبًا بك في عالمي الرقمي</h1>
    <nav>
      <a href="#about">من أنا</a>
      <a href="#projects">مشاريعي</a>
      <a href="#contact">تواصل</a>
    </nav>
  </header>

  <section id="about">
    <h2>من أنا</h2>
    <p>أنا أحمد، مهتم بالمشاريع العقارية والتقنية وأسعى دائمًا لتطوير أدوات عملية وفعّالة.</p>
  </section>

  <section id="projects">
    <h2>مشاريعي</h2>
    <div class="card">
      <h3>مشروع Sky1</h3>
      <p>مشروع عقاري في حي ظهرة لبن بالرياض يجمع بين السكني والتجاري.</p>
    </div>
    <div class="card">
      <h3>أداة إدارة المشاريع</h3>
      <p>ملف Excel جاهز لتوثيق ومتابعة المشاريع بكفاءة.</p>
    </div>
  </section>

  <section id="contact">
    <h2>تواصل معي</h2>
    <button class="btn" onclick="alert('راسلني على البريد: info@example.com')">أرسل رسالة</button>
  </section>

  <footer>
    <p>كل فكرة عظيمة تبدأ بخطوة صغيرة.</p>
  </footer>

</body>
</html>
