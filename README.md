<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Valentine's Day</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Arial', sans-serif;
      color: white;
      flex-direction: column;
    }
    h1 {
      font-size: 3em;
      text-align: center;
      animation: heartbeat 1s infinite;
    }
    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    .heart {
      color: red;
      font-size: 2em;
      margin-top: 10px;
      animation: pulse 1s infinite;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.5); }
    }
  </style>
</head>
<body>
  <h1>Happy Valentine's Day!</h1>
  <div class="heart">❤️</div>
</body>
</html>
