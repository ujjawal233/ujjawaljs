<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Digital Clock</title>
  <style>
    body {
      background: #222;
      display: flex;
      height: 100vh;
      align-items: center;
      justify-content: center;
      margin: 0;
    }
    .clock {
      color: #fff;
      font-family: 'Courier New', Courier, monospace;
      font-size: 4em;
      background: #333;
      padding: 30px 50px;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.5);
      letter-spacing: 0.1em;
    }
  </style>
</head>
<body>
  <div class="clock" id="clock">00:00:00</div>
  <script>
    function updateClock() {
      const now = new Date();
      let h = String(now.getHours()).padStart(2, '0');
      let m = String(now.getMinutes()).padStart(2, '0');
      let s = String(now.getSeconds()).padStart(2, '0');
      document.getElementById('clock').textContent = `${h}:${m}:${s}`;
    }
    setInterval(updateClock, 1000);
    updateClock(); // initial call
  </script>
</body>
</html>
