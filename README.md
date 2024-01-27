# RKTECH-WEB-DEVELOPMENT-task-1 code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Landing Page</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: #f4f4f4;
    }

    header {
      background-color: #566937;
      color: rgb(255, 255, 255);
      text-align: center;
      padding: 1em;
    }

    section {
      display: flex;
      justify-content: space-around;
      padding: 2em;
    }

    .column {
      flex: 1;
      padding: 1em;
      background-color: #ffffff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      margin: 1em;
      border-radius: 8px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Company Name</h1>
    <p>Welcome to our amazing website!</p>
  </header>

  <section>
    <div class="column">
      <h2>Column 1</h2>
      <p>This is some content for the first column.</p>
    </div>

    <div class="column">
      <h2>Column 2</h2>
      <p>This is some content for the second column.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Your Company Name. All rights reserved.</p>
  </footer>

</body>
</html>
