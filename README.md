<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Retro Mac Portfolio</title>
  <style>
    body {
      background-color: #ececec;
      font-family: 'Courier New', Courier, monospace;
      margin: 0;
      padding: 0;
      color: #000;
    }
    .desktop {
      background-color: #d3d3d3;
      min-height: 100vh;
      padding: 40px;
      box-sizing: border-box;
    }
    .window {
      background: #fff;
      border: 2px solid #000;
      width: 700px;
      margin: 0 auto;
      box-shadow: 8px 8px 0px #000;
    }
    .title-bar {
      background: linear-gradient(to right, #c0c0c0, #aaa);
      padding: 5px 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #000;
      font-weight: bold;
    }
    .title-bar-buttons span {
      display: inline-block;
      width: 12px;
      height: 12px;
      background: #000;
      margin-left: 4px;
    }
    .window-content {
      padding: 20px;
    }
    nav {
      margin: 20px 0;
      text-align: center;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #000;
      border: 1px solid #000;
      padding: 4px 8px;
      background: #e0e0e0;
    }
    h1, h2 {
      margin: 0;
      margin-bottom: 10px;
      border-bottom: 1px dashed #000;
      padding-bottom: 5px;
    }
    .project-box {
      border: 1px solid #000;
      padding: 10px;
      background: #f7f7f7;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      font-size: 12px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <div class="desktop">
    <div class="window">
      <div class="title-bar">
        <div>Portfolio</div>
        <div class="title-bar-buttons">
          <span></span><span></span><span></span>
        </div>
      </div>
      <div class="window-content">
        <nav>
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#projects">Projects</a>
          <a href="#contact">Contact</a>
        </nav>

        <h1>John Doe</h1>
        <p>Hi! I’m John, a creative web developer blending retro vibes and modern tech.</p>

        <h2 id="about">About Me</h2>
        <p>I'm passionate about reviving classic UI design like the original Macintosh. This portfolio is built to reflect that spirit—reborn with HTML5 & CSS3.</p>

        <h2 id="projects">Projects</h2>
        <div class="project-box">
          <strong>Mac OS Tribute Page</strong>
          <p>A fully functional retro Mac UI tribute with CSS-only styling.</p>
        </div>
        <div class="project-box">
          <strong>Typewriter Blog</strong>
          <p>A blog styled with a vintage typewriter aesthetic.</p>
        </div>

        <h2 id="contact">Contact</h2>
        <p>Email me at: <strong>john.doe@example.com</strong></p>
      </div>
    </div>

    <footer>
      &copy; 2025 John Doe. Inspired by classic Macintosh, modified for the modern web.
    </footer>
  </div>
</body>
</html>
