# Pyeer
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Payeer Style Page</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
    }

    header {
      background: #0c2d48;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #145374;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
      background: white;
      margin-top: 20px;
      border-radius: 10px;
    }

    .card {
      background: #e8f0fe;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 20px;
      text-align: center;
    }

    .btn {
      background: #00a8ff;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      text-decoration: none;
    }

    .btn:hover {
      background: #007bb5;
    }
  </style>
</head>
<body>

  <header>
    <h1>Payeer Style</h1>
    <p>Demo UI for Educational Use</p>
  </header>

  <nav>
    <a href="#">Dashboard</a>
    <a href="#">Send</a>
    <a href="#">Receive</a>
    <a href="#">History</a>
  </nav>

  <div class="container">
    <div class="card">
      <h2>Balance</h2>
      <p>$0.00</p>
      <a href="#" class="btn">Top Up</a>
    </div>

    <div class="card">
      <h2>Send Money</h2>
      <p>Transfer funds to another user.</p>
      <a href="#" class="btn">Send Now</a>
    </div>
  </div>

</body>
</html>
