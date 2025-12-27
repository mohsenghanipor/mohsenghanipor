
<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>My GitHub Profile</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .card {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 40px;
      max-width: 420px;
      width: 90%;
      text-align: center;
      box-shadow: 0 20px 40px rgba(0,0,0,0.3);
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #fff;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 1.8rem;
      margin-bottom: 8px;
    }

    p {
      font-size: 0.95rem;
      opacity: 0.85;
      margin-bottom: 25px;
      line-height: 1.6;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      margin-bottom: 30px;
    }

    .skill {
      background: rgba(255,255,255,0.15);
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 0.8rem;
    }

    .links a {
      text-decoration: none;
      color: #fff;
      margin: 0 10px;
      padding: 10px 18px;
      border-radius: 25px;
      background: #00c6ff;
      background: linear-gradient(135deg, #00c6ff, #0072ff);
      transition: transform 0.2s, box-shadow 0.2s;
      display: inline-block;
    }

    .links a:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }

    footer {
      margin-top: 25px;
      font-size: 0.75rem;
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <div class="card">
    <img class="avatar" src="https://avatars.githubusercontent.com/u/000000?v=4" alt="avatar">

    <h1>mohsenghanipor</h1>
    <p>
      Frontend Developer • عاشق کد تمیز  
      <br>
      HTML • CSS • JavaScript
    </p>

    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Git</div>
      <div class="skill">React</div>
    </div>

    <div class="links">
      <a href="https://github.com/username" target="_blank">GitHub</a>
      <a href="#" target="_blank">Portfolio</a>
    </div>

    <footer>
      © 2025 • Made with ❤️
    </footer>
  </div>

</body>
</html>
