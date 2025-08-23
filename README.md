# surya-samyog
<!-- Cyberpunk / Neon Green GitHub Profile README -->

<p align="center">
  <img src="./neon_header.svg" alt="Neon header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&center=true&vCenter=true&width=720&lines=Building+ML+%E2%80%A2+Simulations+%E2%80%A2+Materials;Always+in+Cyberpunk+Green+%E2%9A%A1;Open+to+collab+%2F+research+ideas" alt="typing svg">
</p>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glitch Links</title>
  <style>
    body {
      background: black;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: monospace;
    }

    a {
      position: relative;
      font-size: 2rem;
      color: #39ff14; /* neon green */
      text-decoration: none;
      margin: 15px 0;
      letter-spacing: 2px;
      display: inline-flex;
      align-items: center;
    }

    a::after {
      content: " ➜"; /* arrow indicator */
      margin-left: 8px;
      color: #39ff14;
    }

    /* glitch animation */
    a::before {
      content: attr(data-text);
      position: absolute;
      left: 2px;
      text-shadow: -2px 0 #ff00c1;
      top: 0;
      color: #39ff14;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      animation: glitch 2s infinite linear alternate-reverse;
    }

    @keyframes glitch {
      0% {
        clip: rect(20px, 9999px, 21px, 0);
      }
      20% {
        clip: rect(60px, 9999px, 61px, 0);
      }
      40% {
        clip: rect(10px, 9999px, 11px, 0);
      }
      60% {
        clip: rect(40px, 9999px, 41px, 0);
      }
      80% {
        clip: rect(30px, 9999px, 31px, 0);
      }
      100% {
        clip: rect(50px, 9999px, 51px, 0);
      }
    }
  </style>
</head>
<body>
  <a href="mailto:psuryasamyog@gmail.com" data-text="Email">Email</a>
  <a href="https://instagram.com/suryasamyog" target="_blank" data-text="Instagram">Instagram</a>
  <a href="resume.pdf" target="_blank" data-text="Resume">Resume</a>
</body>
</html>
