<body data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="50">
    <!-- NAVBAR -->
    <main>
      <nav id="navbar" class="navbar navbar-expand-lg navbar-dark fixed-top">
        <div class="container flex-lg-column">
          <a class="navbar-brand mx-lg-auto mg-lg-4" href="#">
            <span class="h3 fw-bold d-block d-lg-none">Peter Nguyen</span>
            <img src="/0.png" class="home-img d-none d-lg-block rounded-circle" alt=""/>
          </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto flex-lg-column text-lg-center">
              <li class="nav-item">
                <a class="nav-link" href="/">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#projects">Projects</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <!--//NAVBAR-->
  
      <!--CONTENT WRAPPER-->
      <div id="content-wrapper">
        <!--HOME-->
        <section id="home" class="full-height px-lg-5">
            <div class="row">
              <div class="col-lg-8">
                <div data-aos="fade-up" data-aos-delay="300">
                  <h1 class="display-4 fw-bold">
                    I'm a <span class="text-brand">Software Engineer</span> from Baton Rouge, Louisiana
                  </h1>
                  <p class="lead mt-2 mb-4">
                    I am Peter, an aspiring Software Engineer at LSU graduating in May 2026.
                  </p>
                  <a href="#projects" class="btn btn-brand me-3">Explore my Projects</a>
                  <!-- svelte-ignore a11y-missing-attribute -->
                  <a class="email-link">Contact: peternguyensmhs@gmail.com</a>
                </div>
              </div>
            </div>
        </section>
        <!--//HOME-->
        <!--PROJECTS-->
        <section id="projects" class="full-height px-lg-5">
            <div>
              <div class="container">
                <div class="row">
                  <div data-aos="fade-right">
                    <h6 class="header-text">PROJECTS</h6>
                    <h1>My Projects:</h1>
                    <div class="display">
                      <div class="article-container">
                        
                        <div data-aos="fade-right">
                          <article class="project-card d-flex flex-column flex-md-row align-items-center">
                            <div class="left-article col-12 col-md-6">
                              <header>AniFinder</header>
                              <div>
                                <img class="skill-image" alt="HTML" src="https://img.shields.io/badge/HTML-dee0e3?logo=html5" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="CSS" src="https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript" style="width: 60px; height: 20px;" />
                                <img alt="Svelte" src="https://img.shields.io/badge/Svelte-orange?logo=Svelte&logoColor=orange" />
                              </div>
                              <p>AniFinder is an AI-powered Anime generator based on the user's preferences. The generator is powered by Google's AI, Gemini Pro. The prompts include an anime genre and reference anime to generate a similar anime the user may enjoy.</p>
                              <footer>
                                <a href="https://github.com/peterN12g/anime" class="github" target="_blank"><i class="bi bi-github" style="font-size: 30px;"></i></a>
                                <a href="https://anifinder.peternguyen.tech/" target="_blank"><i class="bi bi-browser-chrome" style="font-size: 30px;"></i></a>
                              </footer>
                            </div>
                            <div class="right-article col-12 col-md-6">
                              <a href="https://anifinder.peternguyen.tech/" target="_blank"><img class="article-img" src="anifind.png" /></a>
                            </div>
                          </article>
                        </div>
          
                        <div data-aos="fade-right">
                          <article class="project-card d-flex flex-column flex-md-row align-items-center">
                            <div class="left-article col-12 col-md-6">
                              <header>GymShark Scraper</header>
                              <div>
                                <img class="skill-image" alt="HTML" src="https://img.shields.io/badge/HTML-dee0e3?logo=html5" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="CSS" src="https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript" style="width: 60px; height: 20px;" />
                                <img alt="Python" src="https://img.shields.io/badge/Python-white?logo=Python&logoColor=blue%2Cyellow" />
                                <img alt="React" src="https://img.shields.io/badge/React-lightgray?logo=React" />
                                <img alt="Flask" src="https://img.shields.io/badge/Flask-lightgray?logo=Flask&logoColor=aqua" />
                              </div>
                              <p>A Python-based web scraper focused on GymShark products. The server is hosted using Python Flask, with Caddy used to reverse proxy over HTTPS. The backend Python server provides data via an API endpoint. The frontend, built with React, displays the information on a webpage and includes a Progressive Web App (PWA) that sends browser notifications through a service worker.</p>
                              <footer>
                                <a href="https://github.com/peterN12g/GymShark-Scraper" target="_blank"><i class="bi bi-github" style="font-size: 30px;"></i></a>
                                <a href="https://gymshark-scraper.peternguyen.tech/" target="_blank"><i class="bi bi-browser-chrome" style="font-size: 30px;"></i></a>
                              </footer>
                            </div>
                            <div class="right-article col-12 col-md-6">
                              <a href="https://gymshark-scraper.peternguyen.tech/" target="_blank"><img class="article-img" src="gymscrape.png" /></a>
                            </div>
                          </article>
                        </div>
          
                        <div data-aos="fade-right">
                          <article class="project-card d-flex flex-column flex-md-row align-items-center">
                            <div class="left-article col-12 col-md-6">
                              <header>Warmup Calculator</header>
                              <div>
                                <img class="skill-image" alt="HTML" src="https://img.shields.io/badge/HTML-dee0e3?logo=html5" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="CSS" src="https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript" style="width: 60px; height: 20px;" />
                                <img alt="Svelte" src="https://img.shields.io/badge/Svelte-orange?logo=Svelte&logoColor=orange" />
                              </div>
                              <p>A simple weightlifting warmup calculator to help lifters work up to their personal best attempt safely. The calculator works seamlessly on mobile as a Progressive Web App (PWA) for user convenience.</p>
                              <footer>
                                <a href="https://github.com/peterN12g/warmupCalc" target="_blank"><i class="bi bi-github" style="font-size: 30px;"></i></a>
                                <a href="https://warmup.peternguyen.tech" target="_blank"><i class="bi bi-browser-chrome" style="font-size: 30px;"></i></a>
                              </footer>
                            </div>
                            <div class="right-article col-12 col-md-6">
                              <a href="https://warmup.peternguyen.tech/" target="_blank"><img class="article-img" src="warmup.png" /></a>
                            </div>
                          </article>
                        </div>
          
                        <div data-aos="fade-right">
                          <article class="project-card d-flex flex-column flex-md-row align-items-center ng-star-inserted">
                            <div class="left-article col-12 col-md-6">
                              <header>Nutrition Tracker</header>
                              <div>
                                <img class="skill-image" alt="HTML" src="https://img.shields.io/badge/HTML-dee0e3?logo=html5" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="CSS" src="https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue" style="width: 40px; height: 20px;" />
                                <img class="skill-image" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript" style="width: 60px; height: 20px;" />
                                <img alt="Svelte" src="https://img.shields.io/badge/Svelte-orange?logo=Svelte&logoColor=orange" />
                              </div>
                              <p>The nutrition tracker provides users the ability to calculate their basal metabolic rate (BMR) and lose weight with the calorie tracker. Information about meals is API returned. Users can add specific foods, which then subtract the provided macronutrients from their daily goals.</p>
                              <footer>
                                <a href="https://github.com/peterN12g/nutritiontrack" target="_blank"><i class="bi bi-github" style="font-size: 30px;"></i></a>
                              </footer>
                            </div>
                            <div class="right-article col-12 col-md-6">
                              <!-- Add image if necessary -->
                            </div>
                          </article>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
        </section>          
        <!--//PROJECTS-->
        <!--ABOUT-->
        <section id="about" class="full-height px-lg-5">
            <div class='container'>
                <div class='row'>
                    <h1>About me:</h1>
                    <img class='about_image' src='fishing.jpg' alt='fishing'>
                    <div class='articles'>
                        <article class='about_container'>
                            <p style='margin-top: 20px;'>I'm Peter, an aspiring Software Engineer at LSU. I graduate in May 2026 with a B.S in Computer Science.
                            In my free time I powerlift with friends, go fishing at grand isle, and program to relax my mind. I began programming with Java,
                            though I've become accustomed to HTML/CSS, JavaScript, and Python, which is my current preferred coding language.
                            That's it about me for now, take time to take a look at my resume or projects to see what I've been working on.
                            </p>
                        </article>
                        <article class='about_container'>
                        </article>
                    </div>
                </div>
            </div>
        </section> 

            <!--ABOUT-->
    </div>
    <!--//CONTENT WRAPPER-->
    </main>
</body>
  
<style>
/*NAVBAR*/
.navbar {
background-color: var(--color-base);
}
.navbar .nav-link {
font-weight: 700;
text-transform: uppercase;
color: white;
}
.navbar .nav-link:hover {
color: var(--color-brand);
}
@media (min-width: 992px) {
.navbar {
    min-height: 100vh;
    width: var(--sidbar-width);
    background: linear-gradient(rgba(3, 63, 71, 0.8), rgba(3, 63, 71, 0.8)),
    url(/sidebar-img.png);
    background-size: cover;
    background-position: center;
}
}
.navbar-brand img {
border: 8px solid var(--color-body);
}
.home-img {
width: 90%;
margin-left: 5%;
}
/*Content Record*/
#content-wrapper {
padding-left: var(--sidbar-width);
}
/*BTN*/
.btn {
padding: 12px 28px;
font-weight: 700;
}
.btn-brand {
background-color: var(--color-brand);
border-color: var(--color-brand);
color: var(--color-base);
}
.btn-brand:hover,
.btn-brand:focus {
background-color: var(--color-brand2);
color: var(--color-base);
border-color: var(--color-brand);
}
.email-link {
font-weight: 700;
position: relative;
}
.email-link::after {
content: "";
width: 0;
height: 2px;
background-color: var(--color-brand);
position: absolute;
left: 0;
top: 110%;
transform: all 0.4s;
}
.email-link:hover::after {
width: 100%;
}
/*PROJECTS*/
article {
flex: auto;
min-height: 200px;
border-radius: 15px;
padding: 50px;
text-align: center;
border: 1px solid black;
display: flex;
flex-direction: column;
background-color: #343a40;
margin-top: 20px;
}
.article-container {
display: flex;
flex-wrap: wrap;
gap: 10px;
justify-content: center;
}
article header {
font-size: 30px;
}
article p {
flex: 1;
}
article footer {
display: flex;
}
article a {
color: inherit;
padding: 8px;
}
.right-article img {
max-width: 100%;
height: auto; /* Maintain aspect ratio */
}
.article-img {
border-radius: 15px;
}
.about_image {
    border-radius: 15px;
}
.about_container {
    width: 50%;
    font-size: 1.1em;
    padding: 10px;
    margin-left: 10px;
    height: 100%;
}
.articles {
    flex-direction: row;
    display: flex;
}
swiper-container {
    width: 100%;
}
</style>