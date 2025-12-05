<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>رایان‌سرا – آموزش ویندوز 10 و مهارت‌های کامپیوتری</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Vazirmatn:wght@400;600;700&display=swap');

    body {
      margin: 0;
      font-family: 'Vazirmatn', sans-serif;
      background: linear-gradient(135deg, #0e0e0e, #1a1f2b, #0d2b4f);
      background-size: 300% 300%;
      animation: bgMove 12s ease infinite;
      color: #fff;
    }

    @keyframes bgMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      padding: 25px;
      text-align: center;
    }

    header h1 {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 32px;
      color: #0d74ff;
      letter-spacing: 2px;
      margin: 0;
    }

    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 40px;
      flex-wrap: wrap;
    }

    .text-box {
      max-width: 45%;
      line-height: 1.9;
      animation: fadeIn 1.5s ease;
    }

    .text-box h1 {
      font-size: 36px;
      margin-bottom: 20px;
      font-weight: 700;
      color: #0d74ff;
    }

    .text-box p {
      font-size: 18px;
      margin-bottom: 15px;
    }

    .hero-img {
      max-width: 50%;
      text-align: center;
      animation: slideUp 1.5s ease;
    }

    .hero-img img {
      width: 420px;
      border-radius: 20px;
      box-shadow: 0 0 35px rgba(0,0,0,0.6);
      transition: transform 0.4s;
    }

    .hero-img img:hover {
      transform: scale(1.05);
    }

    .btn {
      margin-top: 25px;
      padding: 14px 26px;
      border-radius: 14px;
      background: linear-gradient(135deg, #0d74ff, #00c6ff);
      color: #fff;
      border: none;
      font-size: 18px;
      cursor: pointer;
      transition: 0.3s;
      font-weight: 600;
    }

    .btn:hover { background: linear-gradient(135deg, #0a5ed8, #0099cc); }

    footer {
      margin-top: 40px;
      text-align: center;
      padding: 25px;
      background: rgba(255,255,255,0.05);
      font-size: 14px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <h1>Rayan Sara</h1>
</header>

<div class="container">
  <div class="text-box">
    <h1>آموزش حرفه‌ای کامپیوتر و ویندوز 10</h1>
    <p>
      در رایان‌سرا، تمامی آموزش‌ها بر پایه <strong>ویندوز 10</strong> هستند، چون سیستم من هم ویندوز 10 می‌باشد
      و تمام نکات و آموزش‌ها دقیقاً مطابق چیزی است که خودم از آن استفاده می‌کنم.
    </p>
    <p>
      همچنین آموزش‌های صفر تا صد کار با کامپیوتر، نصب نرم‌افزار، کاربردهای مهم، نکات کاربردی و میانبرها نیز ارائه می‌شود.
    </p>
    <button class="btn">شروع آموزش‌ها</button>
  </div>

  <div class="hero-img">
    <!-- تصویر لپ‌تاپ ویندوز 10 با منوی استارت باز -->
    <img src="laptop-win10.png" alt="Laptop Windows 10 Start Menu" />
  </div>
</div>

<footer>
  © 2025 رایان‌سرا – آموزش کاربردی کامپیوتر
</footer>

</body>
</html>
