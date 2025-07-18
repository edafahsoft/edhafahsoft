<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Navbar</title>
  <style>
    body {
      background-color: #121212;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .navbar {
      display: flex;
      background-color: #1e1e1e;
      padding: 12px 20px;
      justify-content: center;
    }

    .navbar a {
      color: #ccc;
      text-decoration: none;
      padding: 10px 15px;
      border-radius: 4px;
      transition: 0.3s;
      margin: 0 5px;
      font-weight: 500;
    }

    .navbar a:hover,
    .navbar a.active {
      color: white;
      background-color: #007aff;
    }
  </style>
</head>
<body>

  <div class="navbar">
    <a href="#" class="active">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
    <a href="#">Assignment</a>
    <a href="#">Blog</a>
    <a href="#">Gallery</a>
    <a href="#">Download</a>
    <a href="#">Project</a>
  </div>

</body>
</html>
