<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>🎙️ قارئ النصوص الخاص بي - يونس</title>
  <style>
    body { 
      font-family: "Tahoma", sans-serif; 
      text-align: center; 
      padding: 20px; 
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      min-height: 100vh;
      margin: 0;
    }
    .card {
      background: white;
      border-radius: 20px;
      padding: 20px;
      max-width: 600px;
      margin: 20px auto;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }
    h1 {
      color: #ff6600;
      margin-bottom: 10px;
    }
    p {
      font-size: 16px;
      color: #333;
    }
    textarea {
      width: 90%; 
      height: 100px; 
      padding: 10px;
      font-size: 18px;
      border-radius: 10px;
      border: 1px solid #ccc;
      margin: 15px 0;
    }
    button {
      padding: 12px 25px;
      font-size: 18px;
      border: none;
      border-radius: 12px;
      background: #ff6600;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover { background: #cc5200; }
    footer {
      margin-top: 25px;
      font-size: 14px;
      color: #444;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>👋 مرحبا بيكم!</h1>
    <p>أنا يونس ✨، ها هو مشروعي الصغير: برنامج يقرأ النصوص بصوت مضحك!  
    شكرا بزاف لكل واحد جرب التطبيق 🌟</p>

    <textarea id="textInput" placeholder="✍️ اكتب نصك هنا..."></textarea><br>
    <button onclick="speakText()">🎤 إقرأ النص</button>
  </div>

  <footer>
    <p>© 2025 — مشروع شخصي من عند يونس.</p>
    <p>😂 استمتعوا بالأصوات المضحكة وشاركوها مع صحابكم!</p>
  </footer>

  <script>
    function speakText() {
      const text = document.getElementById("textInput").value;
      if (!text) {
        alert("أكتب حاجة باش نقراها 😅");
        return;
      }

      const utterance = new SpeechSynthesisUtterance(text);

      // نلعب شوية في الصوت باش يبان مضحك
      utterance.pitch = Math.random() * 2;   
      utterance.rate = 0.8 + Math.random(); 

      speechSynthesis.speak(utterance);
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>🎙️ قارئ النصوص الخاص بي - يونس</title>
  <style>
    body { 
      font-family: "Tahoma", sans-serif; 
      text-align: center; 
      padding: 20px; 
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      min-height: 100vh;
      margin: 0;
    }
    .card {
      background: white;
      border-radius: 20px;
      padding: 20px;
      max-width: 600px;
      margin: 20px auto;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }
    h1 {
      color: #ff6600;
      margin-bottom: 10px;
    }
    p {
      font-size: 16px;
      color: #333;
    }
    textarea {
      width: 90%; 
      height: 100px; 
      padding: 10px;
      font-size: 18px;
      border-radius: 10px;
      border: 1px solid #ccc;
      margin: 15px 0;
    }
    button {
      padding: 12px 25px;
      font-size: 18px;
      border: none;
      border-radius: 12px;
      background: #ff6600;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover { background: #cc5200; }
    footer {
      margin-top: 25px;
      font-size: 14px;
      color: #444;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>👋 مرحبا بيكم!</h1>
    <p>أنا يونس ✨، ها هو مشروعي الصغير: برنامج يقرأ النصوص بصوت مضحك!  
    شكرا بزاف لكل واحد جرب التطبيق 🌟</p>

    <textarea id="textInput" placeholder="✍️ اكتب نصك هنا..."></textarea><br>
    <button onclick="speakText()">🎤 إقرأ النص</button>
  </div>

  <footer>
    <p>© 2025 — مشروع شخصي من عند يونس.</p>
    <p>😂 استمتعوا بالأصوات المضحكة وشاركوها مع صحابكم!</p>
  </footer>

  <script>
    function speakText() {
      const text = document.getElementById("textInput").value;
      if (!text) {
        alert("أكتب حاجة باش نقراها 😅");
        return;
      }

      const utterance = new SpeechSynthesisUtterance(text);

      // نلعب شوية في الصوت باش يبان مضحك
      utterance.pitch = Math.random() * 2;   
      utterance.rate = 0.8 + Math.random(); 

      speechSynthesis.speak(utterance);
    }
  </script>
</body>
</html>
