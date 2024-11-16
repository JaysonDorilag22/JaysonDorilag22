<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jayson Dorilag's Profile</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- For Sun/Moon Icons -->
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .light-theme {
      background-color: #f4f4f9;
      color: #333;
    }

    .dark-theme {
      background-color: #333;
      color: #f4f4f9;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 0;
    }

    h1 {
      font-size: 1.5rem;
    }

    .theme-toggle {
      font-size: 1.5rem;
      cursor: pointer;
    }

    .tech-stack img {
      width: 40px;
      margin: 0 15px;
    }

    .tech-stack {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .current-project a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0A4D68;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
    }

    .stats img {
      width: 100%;
    }

    footer {
      text-align: center;
      margin-top: 40px;
    }

    .contact-icons img {
      width: 40px;
      margin: 0 10px;
      cursor: pointer;
    }

    .footer-wave img {
      width: 50px;
      margin-top: 20px;
    }

    .minimalist {
      text-align: center;
    }

    .minimalist img {
      width: 150px;
    }
  </style>
</head>
<body class="light-theme">

  <div class="container">
    <header>
      <h1>👋 Hi there, I'm Jayson Dorilag</h1>
      <div class="theme-toggle" onclick="toggleTheme()">
        <i id="theme-icon" class="fas fa-sun"></i> <!-- Default to Sun Icon -->
      </div>
    </header>

    <div class="minimalist">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&pause=1000&color=0A4D68&width=435&lines=MERN+Stack+Developer;Web+%26+Mobile+App+Builder;Passionate+About+Problem-Solving" alt="Typing SVG">
    </div>

    <section class="tech-stack">
      <h3>🛠️ Tech Stack</h3>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" alt="React">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original-wordmark.svg" alt="Git">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original-wordmark.svg" alt="Postman">
    </section>

    <section class="current-project">
      <h3>🌟 Current Project</h3>
      <a href="https://github.com/JaysonDorilag22/AgapayAlert">
        <p>A missing person reporting app inspired by Amber Alert, focusing on community safety and real-time notifications.</p>
      </a>
    </section>

    <footer>
      <h3>📫 Let's Connect!</h3>
      <div class="contact-icons">
        <a href="mailto:your-email@example.com">
          <img src="https://img.icons8.com/?size=100&id=P7UIlhbpWzZm&format=png&color=ffffff" alt="Gmail Logo">
        </a>
        <a href="https://github.com/JaysonDorilag22">
          <img src="https://img.icons8.com/?size=100&id=4Z2nCrz5iPY2&format=png&color=ffffff" alt="GitHub Logo">
        </a>
        <a href="https://www.linkedin.com/in/your-linkedin-profile">
          <img src="https://img.icons8.com/?size=100&id=13930&format=png&color=ffffff" alt="LinkedIn Logo">
        </a>
      </div>

      <div class="footer-wave">
        <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Wave" />
      </div>
    </footer>
  </div>

  <script>
    function toggleTheme() {
      const body = document.body;
      const icon = document.getElementById('theme-icon');

      if (body.classList.contains('light-theme')) {
        body.classList.remove('light-theme');
        body.classList.add('dark-theme');
        icon.classList.remove('fa-sun');
        icon.classList.add('fa-moon');
      } else {
        body.classList.remove('dark-theme');
        body.classList.add('light-theme');
        icon.classList.remove('fa-moon');
        icon.classList.add('fa-sun');
      }
    }
  </script>
</body>
</html>
