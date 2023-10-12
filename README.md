# goit-markup-hw-02


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>WebStudio</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/2.0.0/modern-normalize.min.css"
      integrity="sha512-4xo8blKMVCiXpTaLzQSLSw3KFOVPWhm/TRtuPVc4WG6kUgjH6J03IBuG7JZPkcWMxJ5huwaBpOpnwYElP/m6wg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />

    <link rel="stylesheet" href="./css/styles.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <header class="header">
      <nav class="header-navigation">
        <a href="./index.html" class="header-logo"
          >Web
          <span class="header-logo-studio">Studio</span>
        </a>
        <ul class="header-menu-list">
          <li class="header-menu-item">
            <a class="header-menu-link" href="./index.html">Studio</a>
          </li>
          <li class="header-menu-item">
            <a class="header-menu-link" href="">Portfolio</a>
          </li>
          <li class="header-menu-item">
            <a class="header-menu-link" href="">Contacts</a>
          </li>
        </ul>
      </nav>
      <address class="address">
        <ul class="address-menu">
          <li class="address-menu-item">
            <a
              class="address-menu-link"
              href="mailto:info@devstudio.com"
              target="_blank"
              rel="noopenen norefrrer"
              >info@devstudio.com</a
            >
          </li>
          <li class="address-menu-item">
            <a
              class="address-menu-link"
              href="tel:+110001111111"
              target="_blank"
              rel="noopenen norefrrer"
              >+11 (000) 111-11-11</a
            >
          </li>
        </ul>
      </address>
    </header>
    <main class="main-page">
      <section class="solution">
        <h1 class="solution-title">Effective Solutions for Your Business</h1>
        <button class="solution-button" type="button">Order Service</button>
      </section>
      <section class="features">
        <h2 class="visually-hidden">Features</h2>
        <ul class="features-list">
          <li class="features-item">
            <h3 class="features-subtitle">Strategy</h3>
            <p class="features-item-text">
              Our goal is to identify the business problem to walk away with the
              perfect and creative solution.
            </p>
          </li>
          <li class="features-item">
            <h3 class="features-subtitle">Punctuality</h3>
            <p class="features-item-text">
              Bring the key message to the brand's audience for the best price
              within the shortest possible time.
            </p>
          </li>
          <li class="features-item">
            <h3 class="features-subtitle">Diligence</h3>
            <p class="features-item-text">
              Research and confirm brands that present the strongest digital
              growth opportunities and minimize risk.
            </p>
          </li>
          <li class="features-item">
            <h3 class="features-subtitle">Technologies</h3>
            <p class="features-item-text">
              Design practice focused on digital experiences. We bring forth a
              deep passion for problem-solving.
            </p>
          </li>
        </ul>
      </section>
      <section class="team">
        <h2 class="team-title">Our Team</h2>
        <ul class="team-list">
          <li class="team-item">
            <img
              src="./images/team-img.1.jpg"
              alt="Mark Guerrero"
              width="264"
              height="260"
              class="team-img"
            />
            <h3 class="team-subtitle">Mark Guerrero</h3>
            <p class="team-text">Product Designer</p>
          </li>
          <li class="team-item">
            <img
              src="./images/team-img.2.jpg"
              alt="Tom Ford"
              width="264"
              height="260"
              class="team-img"
            />
            <h3 class="team-subtitle">Tom Ford</h3>
            <p class="team-text">Frontend Developer</p>
          </li>
          <li class="team-item">
            <img
              src="./images/team-img.3.jpg"
              alt="Camila Garcia"
              width="264"
              height="260"
              class="team-img"
            />
            <h3 class="team-subtitle">Camila Garcia</h3>
            <p class="team-text">Marketing</p>
          </li>
          <li class="team-item">
            <img
              src="./images/team-img.4.jpg"
              alt="Daniel Wilson"
              width="264"
              height="260"
              class="team-img"
            />
            <h3 class="team-subtitle">Daniel Wilson</h3>
            <p class="team-text">UI Designer</p>
          </li>
        </ul>
      </section>
      <section>
        <h2 class="portfolio">Our Portfolio</h2>
        <ul class="portfolio-list">
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-1.jpg"
              alt="Banking App"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Banking App</h3>
            <p class="portfolio-text">App</p>
          </li>
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-2.jpg"
              alt="Cashless Payment"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Cashless Payment</h3>
            <p class="portfolio-text">Marketing</p>
          </li>
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-3.jpg"
              alt="Meditation App"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Meditation App</h3>
            <p class="portfolio-text">App</p>
          </li>
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-4.jpg"
              alt="Taxi Service"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Taxi Service</h3>
            <p class="portfolio-text">Marketing</p>
          </li>
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-5.jpg"
              alt="Screen Illustrations"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Screen Illustrations</h3>
            <p class="portfolio-text">Design</p>
          </li>
          <li class="portfolio-item">
            <img
              src="./images/portfolio-img-6.jpg"
              alt="Online Courses"
              width="360"
              height="300"
              class="portfolio-item-img"
            />
            <h3 class="portfolio-subtitle">Online Courses</h3>
            <p class="portfolio-text">Marketing</p>
          </li>
        </ul>
      </section>
    </main>
    <footer class="footer">
      <a href="./index.html" class="footer-logo"
        >Web
        <span class="footer-logo-studio">Studio</span>
      </a>
      <p class="footer-text">
        Increase the flow of customers and sales for your business with digital
        marketing & growth solutions.
      </p>
    </footer>
  </body>
</html>
