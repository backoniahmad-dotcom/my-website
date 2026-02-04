<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقع الهكر السفاح</title>
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
      margin: 5px;
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
    .card img {
      width: 60px;
      height: 60px;
      margin-bottom: 10px;
    }
    footer {
      background-color: #1E3A8A;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    iframe {
      border:0;
      width: 100%;
      height: 300px;
      border-radius: 8px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>مرحبًا بك في موقع الهكر المدمر احمد</h1>
    <nav>
      <a href="#about">من أنا</a>
      <a href="#projects">مشاريعي</a>
      <a href="#contact">تواصل</a>
    </nav>
  </header>

  <section id="about">
    <h2>من أنا؟</h2>
    <p>أنا المهندس أحمد ، مهتم بالمشاريع العقارية والتقنية وأسعى دائمًا لتطوير أدوات عملية وفعّالة.</p>
  </section>

  <section id="projects">
    <h2>مشاريعي</h2>
    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/281/281760.png" alt="أيقونة ملف">
      <h3>التهكير</h3>
      <p>جميع انواع التهكير.</p>
    </div>
  </section>

  <!-- صورة BMW M4 -->
  <img src="https://cdn.motor1.com/images/mgl/0ANk0/s1/2021-bmw-m4.jpg" 
       alt="BMW M4" 
       style="width:100%;max-width:700px;display:block;margin:auto;border-radius:10px;">

  <section id="contact">
    <h2>تواصل معي</h2>
    <p><strong>الاسم:</strong> المهندس أحمد</p>
    <p><strong>رقم الهاتف:</strong> +963981877806</p>
    <p><strong>البريد الإلكتروني:</strong> backoniahmad@gmail.com</p>

    <a class="btn" href="https://wa.me/963981877806" target="_blank">تواصل عبر واتساب</a>
    <a class="btn" href="mailto:backoniahmad@gmail.com">أرسل بريد إلكتروني</a>
    <button class="btn" onclick="alert('يمكنك التواصل معي عبر الرقم: +963981877806 أو البريد: backoniahmad@gmail.com')">اتصل الآن</button>

    <!-- عداد زيارات شغال -->
    <div style="margin-top:20px;">
      <p>عدد الزيارات:</p>
      <img src="https://hitwebcounter.com/counter/counter.php?page=11964050&style=0006&nbdigits=5&type=page&initCount=0" 
           title="عداد زيارات" 
           alt="عداد زيارات">
    </div>

    <!-- خريطة Google Maps -->
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d10639.748!2d36.2765!3d33.5138"
      allowfullscreen=""
      loading="lazy">
    </iframe>
  </section>

  <footer>
    <p>كل فكرة عظيمة تبدأ بخطوة صغيرة.</p>
  </footer>

</body>
</html>
