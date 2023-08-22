<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Novita Anggraini</title>
    <style>
      body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #f7f7f7;
      }

      header {
        background-color: #333;
        color: white;
        padding: 1rem 0;
      }

      .main-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 2rem;
      }

      .logo a {
        display: flex;
        align-items: center;
        font-size: 2rem;
        color: white;
        text-decoration: none;
        font-weight: bold;
      }

      .nav {
        display: flex;
        align-items: center;
      }

      .nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        gap: 2rem;
      }

      .nav ul li {
        margin-right: 1.5rem;
      }

      .nav ul li:last-child {
        margin-right: 0;
      }

      .nav ul li a {
        color: white;
        text-decoration: none;
        transition: color 0.3s ease;
      }

      .nav ul li a:hover {
        color: #f39c12;
      }

      .btn {
        background-color: #f39c12;
        color: white;
        border: none;
        padding: 0.5rem 1rem;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s ease;
      }

      .btn:hover {
        background-color: #e67e22;
      }

      #home {
        display: flex;
        align-items: center;
        justify-content: space-around;
        padding: 4rem 0;
        background-color: #fff;
      }

      .home-left {
        max-width: 600px;
        margin-right: 3rem;
      }

      .pre-title {
        color: #f39c12;
        font-size: 1.2rem;
        margin-bottom: 1rem;
      }

      .headline {
        font-size: 2.5rem;
        margin-bottom: 1.5rem;
      }

      .home-right img {
        max-width: 100%;
        height: auto;
        box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
      }
    </style>
  </head>
  <body>
    <!-- Header Start -->
    <header>
      <div class="main-container">
        <div class="logo">
          <a href="/">NA</a>
        </div>
        <nav class="nav">
          <ul>
            <li><a href="#Projects">Projects</a></li>
            <li><a href="#Experiences">Experiences</a></li>
            <li><a href="#Education">Education</a></li>
            <li><a href="#Contact">Contact</a></li>
            <li>
              <a href="https://drive.google.com/file/d/1SpA91Nkm7dJ7FEQYnnYq7us3ggn56Ztx/view?usp=sharing" target="_blank">
                <button class="btn">Resume</button>
              </a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
    <!-- Header End -->

    <!-- Hero Start -->
    <section id="home">
      <div class="home-left">
        <h3 class="pre-title">Hi, I'm Novita</h3>
        <h1 class="headline">Unveiling Insights, Crafting Stories</h1>
        <p>As an Informatics engineering student, I dive deep into the realm of data analysis. Armed with a passion for unraveling patterns, I wield SQL, Python, and Power BI as my tools of choice.</p>
      </div>
      <div class="home-right">
        <img src="https://i.postimg.cc/25HxTr8q/Whats-App-Image-2022-09-14-at-23-33-39-removebg-preview-1.png" alt="ME" />
      </div>
    </section>
    <!-- Hero End -->
  </body>
</html>
