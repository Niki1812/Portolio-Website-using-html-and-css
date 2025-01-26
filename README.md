# Portolio-Website-using-html-and-css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NIKITA - Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background-color: rgb(0, 0, 33);
      color: aliceblue;
      font-family: "Poppins", sans-serif;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 80px;
      padding: 0 20px;
      background-color: rgb(18, 18, 64);
    }
    nav img {
      width: 50px;
      border-radius: 50%;
    }
    nav ul {
      display: flex;
      justify-content: center;
    }
    nav ul li {
      list-style: none;
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: white;
      transition: color 0.3s ease-in-out;
    }
    nav ul li a:hover {
      color: rgb(127, 14, 129);
    }
    header {
      text-align: center;
      margin-top: 20px;
    }
    /* Portfolio Logo Styling */
    header img.portfolio-logo {
      width: 100px; /* Size for the logo */
      margin-bottom: 10px;
      transition: transform 0.3s ease-in-out;
    }
    header img.portfolio-logo:hover {
      transform: scale(1.1); /* Logo hover effect */
    }
    header h1 {
      font-size: 2.5rem;
    }
    .firstsection {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 60px 0;
    }
    .leftsection {
      width: 45%;
    }
    .leftsection h1 {
      font-size: 2.5rem;
    }
    .leftsection span.purple {
      color: #ae00ff;
    }
    .leftsection p {
      margin-top: 20px;
      line-height: 1.6;
    }
    .leftsection .buttons {
      margin-top: 30px;
    }
    .btn {
      padding: 10px 20px;
      margin: 10px;
      background-color: #ae00ff53;
      color: white;
      border: 2px solid white;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
      transition: all 0.3s ease-in-out;
    }
    .btn:hover {
      background-color: white;
      color: #ae00ff;
      transform: scale(1.05);
    }
    .rightsection img {
      width: 250px;
      border-radius: 10px;
      transition: transform 0.3s ease-in-out;
    }
    .rightsection img:hover {
      transform: scale(1.1);
    }
    .secondsection {
      text-align: center;
      margin: 40px auto;
      max-width: 90vw;
    }
    .secondsection h1 {
      font-size: 2rem;
      margin: 20px 0;
    }
    .line {
      width: 70%;
      margin: 20px auto;
      height: 2px;
      background-color: white;
    }
    .work-experience-logo {
      width: 100px;
      margin: 10px auto;
      transition: transform 0.3s ease-in-out;
    }
    .work-experience-logo:hover {
      transform: scale(1.1);
    }
    .box {
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      flex-wrap: wrap;
      margin-top: 30px;
    }
    .box .vertical {
      width: 180px;
      text-align: center;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      padding: 20px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .box .vertical:hover {
      transform: scale(1.05);
      box-shadow: 0px 4px 15px rgba(127, 14, 129, 0.4);
    }
    .box .vertical img {
      width: 70px;
      margin-bottom: 10px;
    }
    .box .vertical p {
      margin: 10px 0;
      font-size: 0.9rem;
      color: lightgray;
    }
    footer {
      background-color: rgb(18, 18, 64);
      padding: 30px 20px;
      margin-top: 40px;
      color: gray;
    }
    footer .footer-links {
      display: flex;
      justify-content: space-evenly;
      flex-wrap: wrap;
      text-align: center;
      margin-bottom: 20px;
    }
    footer .footer-links ul {
      list-style: none;
    }
    footer .footer-links ul li {
      margin: 5px 0;
    }
    footer .footer-links ul li a {
      text-decoration: none;
      color: aliceblue;
      transition: color 0.3s ease-in-out;
    }
    footer .footer-links ul li a:hover {
      color: #ae00ff;
    }
    footer .footer-rights {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <nav>
    <img src="https://tse4.mm.bing.net/th?id=OIP.eL-vKUCGZymG2NJjYoUNtQAAAA&pid=Api&P=0&h=180" alt="Profile">
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/">About</a></li>
      <li><a href="/">Services</a></li>
      <li><a href="/">Projects</a></li>
      <li><a href="/">Contact Me</a></li>
    </ul>
  </nav>
  <header>
    <!-- Portfolio Logo Added -->
    <img class="portfolio-logo" src="https://tse1.mm.bing.net/th?id=OIP.P19gtM1iYofy8kiOuuuE5AHaHa&pid=Api&P=0&h=180" alt="Portfolio Logo">
    <h1>Welcome to Nikita's Portfolio</h1>
    <p>I'm Nikita, a full-stack developer passionate about creating efficient, scalable, and user-friendly applications. I excel in both front-end and back-end technologies.</p>
  </header>
  <main>
    <section class="firstsection">
      <div class="leftsection">
        <h1>
          Hi, My name is <span class="purple">Nikita</span>
        </h1>
        <p>and I specialize in building responsive, user-focused applications.</p>
        <div class="buttons">
          <button class="btn">Download Resume</button>
          <button class="btn">Visit Github</button>
        </div>
      </div>
      <div class="rightsection">
        <img src="https://static.vecteezy.com/system/resources/previews/023/485/894/original/web-developer-graphic-clipart-design-free-png.png" alt="Developer Image">
      </div>
    </section>
    <section class="secondsection">
      <img class="work-experience-logo" src="https://cdn-icons-png.flaticon.com/512/1658/1658696.png" alt="Work Experience">
      <h1>Work Experience</h1>
      <div class="line"></div>
      <div class="box">
        <div class="vertical">
          <!-- Corrected C logo -->
          <img src="https://tse1.mm.bing.net/th?id=OIP.F6r9QQCelEOLZDL9vn74DwHaHa&pid=Api&P=0&h=180" alt="C Logo">
          <p>C Developer</p>
          <p>Developed system-level applications using C programming for efficient performance.</p>
        </div>
        <div class="vertical">
          <!-- Corrected C++ logo -->
          <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="C++ Logo">
          <p>C++ Developer</p>
          <p>Created efficient algorithms and real-time systems using C++.</p>
        </div>
        <div class="vertical">
          <img src="https://tse4.mm.bing.net/th?id=OIP.4dQkxLm-cAndV-9OfVjjQwHaE8&pid=Api&P=0&h=180" alt="CSS Logo">
          <p>HTML Developer</p>
          <p>Designed responsive user interfaces.</p>
        </div>
        <div class="vertical">
          <img src="https://logodix.com/logo/1169356.png" alt="CSS Logo">
          <p>CSS Developer</p>
          <p>Designed responsive user interfaces.</p>
        </div>
        <div class="vertical">
          <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Python Logo">
          <p>Python Developer</p>
          <p>Built scalable backend systems and APIs.</p>
        </div>
      </div>
    </section>
  </main>
  <footer>
    <div class="footer-links">
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/">About</a></li>
        <li><a href="/">Contact</a></li>
      </ul>
    </div>
    <div class="footer-rights">
      Copyright &#169; Nikita's Portfolio | All rights reserved
    </div>
  </footer>
</body>
</html>
