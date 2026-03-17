<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VRAM Masters</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: white;
    }

    /* NAVBAR */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: #111;
      position: sticky;
      top: 0;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
    }

    .menu {
      list-style: none;
      display: flex;
      gap: 25px;
    }

    .menu a {
      text-decoration: none;
      color: white;
      transition: 0.3s;
    }

    .menu a:hover {
      color: #00ffcc;
    }

    /* HERO SECTION */
    .hero {
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      color: #aaa;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      background: #00ffcc;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      text-decoration: none;
      color: black;
      display: inline-block;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #777;
    }
  </style>
</head>

<body>

<!-- NAVBAR -->
<nav>
  <div class="logo">VRAM Masters</div>
  <ul class="menu">
    <li><a href="samples.html">Samples</a></li>
    <li><a href="discography.html">Discography</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div>
    <h1>Welcome to VRAM Masters</h1>
    <p>High-quality audio samples, music releases, and creative sound design.</p>
    <a href="samples.html" class="btn">Explore Samples</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 VRAM Masters. All rights reserved.</p>
</footer>

</body>
</html>
