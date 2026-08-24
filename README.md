# test-vps-panel<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VPS Panel</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f1117;
      color: white;
    }

    header {
      padding: 20px;
      background: #171a23;
      font-size: 24px;
      font-weight: bold;
    }

    .container {
      padding: 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }

    .card {
      background: #191d27;
      padding: 20px;
      border-radius: 12px;
    }

    .value {
      font-size: 28px;
      margin-top: 10px;
    }

    button {
      padding: 12px 18px;
      margin: 5px;
      border: 0;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>

<body>

<header>⚡ My VPS Panel</header>

<div class="container">

  <div class="card">
    <div>CPU</div>
    <div class="value">0%</div>
  </div>

  <div class="card">
    <div>RAM</div>
    <div class="value">0 GB</div>
  </div>

  <div class="card">
    <div>Disk</div>
    <div class="value">0 GB</div>
  </div>

  <div class="card">
    <div>Network</div>
    <div class="value">0 KB/s</div>
  </div>

  <div class="card">
    <h3>Server Controls</h3>
    <button>▶ Start</button>
    <button>⏹ Stop</button>
    <button>🔄 Restart</button>
  </div>

</div>

</body>
</html>
