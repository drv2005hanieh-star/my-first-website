
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#0b0b12">
  <meta name="description" content="My developer portfolio and learning projects.">
  <title>Developer Portfolio</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b0b12;
      color: #f5f3ff;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(100% - 36px, 1000px);
      margin: auto;
    }

    header {
      padding: 22px 0;
      border-bottom: 1px solid #272333;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
    }

    .logo {
      color: #c4a5ff;
      font-weight: bold;
      font-size: 20px;
    }

    nav a {
      font-size: 14px;
      color: #c9c4d8;
      margin-left: 14px;
    }

    .hero {
      padding: 90px 0 75px;
    }

    .tag {
      display: inline-block;
      color: #d3baff;
      background: #211832;
      border: 1px solid #493366;
      border-radius: 30px;
      padding: 6px 13px;
      font-size: 13px;
      margin-bottom: 22px;
    }

    h1 {
      font-size: clamp(38px, 8vw, 68px);
      line-height: 1.12;
      letter-spacing: -2px;
      max-width: 700px;
    }

    h1 span {
      color: #b794ff;
    }

    .intro {
      color: #aaa5bb;
      max-width: 540px;
      margin: 22px 0 28px;
    }

    .button {
      display: inline-block;
      padding: 11px 18px;
      border-radius: 9px;
      background: #a879ff;
      color: #140d20;
      font-weight: bold;
      margin: 0 8px 8px 0;
    }

    .button.secondary {
      background: transparent;
      border: 1px solid #514362;
      color: #f5f3ff;
    }

    section {
      padding: 48px 0;
    }

    .section-title {
      font-size: 28px;
      margin-bottom: 8px;
    }

    .section-desc {
      color: #aaa5bb;
      margin-bottom: 25px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 16px;
    }

    .card {
      background: #13121d;
      border: 1px solid #2b2738;
      border-radius: 15px;
      padding: 22px;
    }

    .card h3 {
      color: #d5c2ff;
      margin-bottom: 9px;
    }

    .card p {
      color: #aaa5bb;
      font-size: 14px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      border: 1px solid #49375f;
      background: #1b1627;
      color: #d9c9ff;
      border-radius: 8px;
      padding: 8px 13px;
      font-size: 14px;
    }

    footer {
      border-top: 1px solid #272333;
      padding: 25px 0;
      text-align: center;
      color: #928ca4;
      font-size: 13px;
      margin-top: 35px;
    }

    @media (max-width: 560px) {
      .hero {
        padding: 65px 0 45px;
      }

      .grid {
        grid-template-columns: 1fr;
      }

      nav a {
        margin-left: 8px;
      }

      h1 {
        letter-spacing: -1px;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="container">
      <nav>
        <a class="logo" href="#">dev.portfolio</a>
        <div>
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#projects">Projects</a>
        </div>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="about">
      <div class="container">
        <div class="tag">Welcome to my portfolio ✨</div>

        <h1>
          Hi, I'm a future
          <span>Developer.</span>
        </h1>

        <p class="intro">
          I'm learning web development and cybersecurity.
          This is my journey, my practice, and my growing
          collection of projects.
        </p>

        <a class="button" href="#projects">Explore my work ↘</a>
        <a class="button secondary"
           href="https://github.com/drv2005hanieh-star">
          My GitHub
        </a>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2 class="section-title">My Skills</h2>
        <p class="section-desc">
          Technologies I'm learning step by step.
        </p>

        <div class="skills">
          <span class="skill">HTML</span>
          <span class="skill">CSS</span>
          <span class="skill">JavaScript — learning next</span>
