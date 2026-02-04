<!DOCTYPE html>
<html>
<head>
  <title>For Sahil ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6ee;
      text-align: center;
      padding: 40px;
    }
    h1 { color: #d6336c; }
    button {
      font-size: 18px;
      padding: 12px 25px;
      margin: 15px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
    }
    .yes { background: #ff4d6d; color: white; }
    .no { background: #adb5bd; color: white; }
  </style>
</head>

<body>
  <h1>Sahil 💕</h1>
  <h2>Will you be my Valentine? 🥺❤️</h2>

  <button class="yes" onclick="yesClick()">YES 💖</button>
  <button class="no" onclick="noClick()">NO 😭</button>

  <script>
    function yesClick() {
      document.body.innerHTML = "<h1>YAYYYY 🥹💖</h1><p>You have no idea how happy you just made me.<br>Happy Valentine’s Day, Sahil ❤️🌹</p>";
    }
    function noClick() {
      alert("Nice try 😌 But NO isn’t an option. Press YES 💖");
    }
  </script>
</body>
</html>
