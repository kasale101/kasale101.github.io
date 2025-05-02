<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Novel Site</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #e0e0e0; /* Grey background */
      position: relative;
      overflow-x: hidden;
    }

    /* Watermark */
    body::before {
      content: "kasaleignatius";
      position: fixed;
      top: 30%;
      left: 10%;
      font-size: 100px;
      color: rgba(0, 0, 0, 0.05);
      z-index: 0;
      transform: rotate(-20deg);
      pointer-events: none;
      white-space: nowrap;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 1em 2em;
      text-align: center;
      position: relative;
      z-index: 1;
    }

    nav {
      background-color: #444;
      padding: 0.5em 2em;
      position: relative;
      z-index: 1;
    }

    nav a {
      color: #fff;
      margin-right: 1em;
      text-decoration: none;
    }

    main {
      padding: 2em;
      position: relative;
      z-index: 1;
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 1em 2em;
      margin-top: 2em;
      position: relative;
      z-index: 1;
    }

    .recommendations {
      background-color: #fff;
      padding: 1.5em;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .recommendations h3 {
      margin-top: 0;
    }

    .recommendations ul {
      list-style: none;
      padding: 0;
    }

    .recommendations li {
      margin-bottom: 0.8em;
    }

    .recommendations a {
      color: #0077cc;
      text-decoration: none;
    }

    .recommendations a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Novels</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <h2>Hello there!</h2>
    <p>This site is for novel lovers. Find cool recommendations below!</p>

    <div class="recommendations">
      <h3>Recommended Novel Reading Websites:</h3>
      <ul>
        <li><a href="https://novelbin.me" target="_blank">NovelBin</a></li>
        <li><a href="https://www.webnovel.com" target="_blank">WebNovel</a></li>
        <li><a href="https://mtlnovel.me" target="_blank">MTLNovels</a></li>
      </ul>
    </div>
  </main>

  <footer>
    &copy; 2025 My Novel Site. All rights reserved.
  </footer>

</body>
</html>
