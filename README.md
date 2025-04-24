<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>فيلم العاشرة – شاهد وشارك</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #f8f9fa;
      text-align: center;
      padding: 50px 20px;
    }
    h1 {
      color: #222;
      margin-bottom: 20px;
    }
    p {
      color: #444;
      font-size: 18px;
    }
    .cta-button {
      background-color: #ffcc00;
      color: #000;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 30px;
      transition: 0.3s;
    }
    .cta-button:hover {
      background-color: #e6b800;
    }
    .emoji {
      font-size: 24px;
      margin-left: 8px;
    }
  </style>
</head>
<body>
  <h1>🎬 فيلم العاشرة</h1>
  <p>مشاهدة واحدة منك قد تصنع فرقًا كبيرًا. ساهم بدعم الفيلم من خلال مشاركته مع الآخرين ❤️</p>
  <button class="cta-button" onclick="openLinks()">
    شاهد وشارك وادعم <span class="emoji">😉</span>
  </button>

  <script>
    function openLinks() {
      window.open("https://youtu.be/IBjZo947sJ4", "_blank"); // رابط الفيلم على يوتيوب
      setTimeout(() => {
        window.open("https://www.facebook.com/sharer/sharer.php?u=https://youtu.be/IBjZo947sJ4", "_blank");
      }, 1000);
    }
  </script>
</body>
</html>
