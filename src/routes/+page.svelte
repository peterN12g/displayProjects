<script>
  function openResume(){
      window.open('Resume.pdf', '_blank')
  }
</script>

<body data-bs-spy='scroll' data-bs-target='.navbar' data-bs-offset='50'>
  <!-- NAVBAR -->
  <main>
    <nav id='navbar' class='navbar navbar-expand-lg navbar-dark fixed-top'>
      <div class='container flex-lg-column'>
        <a class='navbar-brand mx-lg-auto mg-lg-4' href='#home'>
          <span class='h3 fw-bold d-block d-lg-none'>Peter Nguyen</span>
          <img src='/0.png' class='home-img d-none d-lg-block rounded-circle' alt=''/>
        </a>
        <button class='navbar-toggler' type='button' data-bs-toggle='collapse' data-bs-target='#navbarNav' aria-controls='navbarNav' aria-expanded='false' aria-label='Toggle navigation'>
          <span class='navbar-toggler-icon'></span>
        </button>
        <div class='collapse navbar-collapse' id='navbarNav'>
          <ul class='navbar-nav ms-auto flex-lg-column text-lg-center'>
            <li class='nav-item'>
              <a class='nav-link' href='/'>Home</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#projects'>Projects</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#about'>About</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#experience'>Experience</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!--//NAVBAR-->
    <!--CONTENT WRAPPER-->
    <div id='content-wrapper'>
    <!--HOME-->
    <section id='home' class='full-height px-lg-5'>
      <div class='row'>
        <div class='col-lg-8'>
          <div>
            <h1 class='display-4 fw-bold'>
              I'm a <span class='text-brand'>Software Engineer</span> from Baton Rouge, Louisiana
            </h1>
            <p class='lead mt-2 mb-4'>
              I am Peter, an aspiring Software Engineer at LSU graduating in May 2026.
            </p>
            <div>
              <p class='intro-flex'>
                <a href='#projects' class='btn btn-brand'>Explore my Projects</a>
                <button class='btn' style='color: white; border-color: var(--color-brand);' on:click={openResume}>View my Resume</button>
              </p>
              </div>
          </div>
        </div>
      </div>
    </section>
    <!--//HOME-->
    <!--PROJECTS-->
    <section id='projects' class='full-height px-lg-5'>
      <div>
        <div class='container'>
          <div class='row'>
            <div>
              <h6 class='header-text'>PROJECTS</h6>
                <h1>My Projects:</h1>
                <div class='display'>
                  <div class='article-container'>    
                    <div>
                      <article class='project-card d-flex flex-column flex-md-row align-items-center'>
                        <div class='left-article col-12 col-md-6'>
                          <header>AniFinder</header>
                          <div>
                            <img class='skill-image' alt='HTML' src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' style='width: 40px; height: 20px;' />
                            <img class='skill-image' alt='CSS' src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' style='width: 40px; height: 20px;' />
                            <img class='skill-image' alt='JavaScript' src='https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript' style='width: 60px; height: 20px;' />
                            <img alt='Svelte' src='https://img.shields.io/badge/Svelte-dee0e3?logo=Svelte' />
                          </div>
                          <p>AniFinder is an AI-powered Anime generator based on the user's preferences. The generator is powered by Google's AI, Gemini Pro. The prompts include an anime genre and reference anime to generate a similar anime the user may enjoy.</p>
                          <footer>
                            <a href='https://github.com/peterN12g/anime' class='github' target='_blank'><i class='bi bi-github' style='font-size: 30px;'></i></a>
                            <a href='https://anifinder.peternguyen.tech/' target='_blank'><i class='bi bi-browser-chrome' style='font-size: 30px;'></i></a>
                          </footer>
                        </div>
                        <div class='right-article col-12 col-md-6'>
                          <a href='https://anifinder.peternguyen.tech/' target='_blank'><img class='article-img' src='anifind.png' alt='anifinder' /></a>
                        </div>
                      </article>
                    </div>  
                    <div>
                      <article class='project-card d-flex flex-column flex-md-row align-items-center'>
                        <div class='left-article col-12 col-md-6'>
                          <header>GymShark Scraper</header>
                          <div>
                            <img alt='HTML' src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' style='width: 40px; height: 20px;' />
                            <img alt='CSS'  src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' style='width: 40px; height: 20px;' />
                            <img alt='JavaScript' src='https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript' style='width: 60px; height: 20px;' />
                            <img alt='Python' src='https://img.shields.io/badge/Python-white?logo=Python&logoColor=blue%2Cyellow'/>
                            <img alt='React' src='https://img.shields.io/badge/React-lightgray?logo=React' />
                            <img alt='Flask' src='https://img.shields.io/badge/Flask-lightgray?logo=Flask&logoColor=aqua' />
                          </div>
                          <p>A Python-based web scraper focused on GymShark products. The server is hosted using Python Flask, with Caddy used to reverse proxy over HTTPS. The backend Python server provides data via an API endpoint. The frontend, built with React, displays the information on a webpage and includes a Progressive Web App (PWA) that sends browser notifications through a service worker.</p>
                          <footer>
                            <a href='https://github.com/peterN12g/GymShark-Scraper' target='_blank'><i class='bi bi-github' style='font-size: 30px;'></i></a>
                            <a href='https://gymshark-scraper.peternguyen.tech/' target='_blank'><i class='bi bi-browser-chrome' style='font-size: 30px;'></i></a>
                          </footer>
                        </div>
                        <div class='right-article col-12 col-md-6'>
                          <a href='https://gymshark-scraper.peternguyen.tech/' target='_blank'><img class='article-img' src='gymscrape.png' alt='gymscraper'/></a>
                        </div>
                      </article>
                      </div>

                      <div>
                        <article class='project-card d-flex flex-column flex-md-row align-items-center'>
                          <div class='left-article col-12 col-md-6'>
                            <header>Warmup Calculator</header>
                            <div>
                              <img class='skill-image' alt='HTML' src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' style='width: 40px; height: 20px;' />
                              <img class='skill-image' alt='CSS' src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' style='width: 40px; height: 20px;' />
                              <img class='skill-image' alt='JavaScript' src='https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript' style='width: 60px; height: 20px;' />
                              <img alt='Svelte' src='https://img.shields.io/badge/Svelte-dee0e3?logo=Svelte' />
                            </div>
                            <p>A simple weightlifting warmup calculator to help lifters work up to their personal best attempt safely. The calculator works seamlessly on mobile as a Progressive Web App (PWA) for user convenience.</p>
                            <footer>
                              <a href='https://github.com/peterN12g/warmupCalc' target='_blank'><i class='bi bi-github' style='font-size: 30px;'></i></a>
                              <a href='https://warmup.peternguyen.tech' target='_blank'><i class='bi bi-browser-chrome' style='font-size: 30px;'></i></a>
                            </footer>
                          </div>
                          <div class='right-article col-12 col-md-6'>
                            <a href='https://warmup.peternguyen.tech/' target='_blank'><img class='article-img' src='warmup.png' alt='warmup'/></a>
                          </div>
                        </article>
                      </div>
        
                      <div>
                        <article class='project-card d-flex flex-column flex-md-row align-items-center ng-star-inserted'>
                          <div class='left-article col-12 col-md-6'>
                            <header>Nutrition Tracker</header>
                            <div>
                              <img class='skill-image' alt='HTML' src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' style='width: 40px; height: 20px;' />
                              <img class='skill-image' alt='CSS' src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' style='width: 40px; height: 20px;' />
                              <img class='skill-image' alt='JavaScript' src='https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript' style='width: 60px; height: 20px;' />
                              <img alt='Svelte' src='https://img.shields.io/badge/Svelte-dee0e3?logo=Svelte' />
                            </div>
                            <p>The nutrition tracker provides users the ability to calculate their basal metabolic rate (BMR) and lose weight with the calorie tracker. Information about meals is API returned. Users can add specific foods, which then subtract the provided macronutrients from their daily goals.</p>
                            <footer>
                              <a href='https://github.com/peterN12g/nutritiontrack' target='_blank'><i class='bi bi-github' style='font-size: 30px;'></i></a>
                            </footer>
                          </div>
                          <div class='right-article col-12 col-md-6'>
                            <img src='nutrition.jpg' alt='nutrition'>
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
    <section id='about' class='full-height px-lg-5'>
      <div class='container'>
        <div class='row'>
          <h6 class='header-text'>ABOUT</h6>
          <h1>About me:</h1>
          <img class='about_image' src='fishing.jpg' alt='fishing'>
          <div class='articles'>
            <article class='about_container' id='about_container_1'>
              <p style='margin-top: 20px; margin-left:10px; margin-right:10px; font-size: 1.2rem;'>I'm Peter, an aspiring Software Engineer at 
                LSU. I graduate in May 2026 with a B.S in Computer Science. In my free time I powerlift with friends, go fishing at grand isle, 
                and program to relax my mind. I began programming with Java, though I've become accustomed to HTML/CSS, JavaScript, and Python, 
                which is my current preferred coding language. That's it about me for now, take time to take a look at my resume or projects to see 
                what I've been working on.
              </p>
            </article>
            <article class='about_container'>
              <div class='tabs'>
                <div class='tab-4'>
                  <label for='tab4-1'>Education</label>
                  <input id='tab4-1' name='tabs' type='radio' checked='checked'>
                  <div>
                    <img  src='https://img.shields.io/badge/Louisiana%20State%20-University%20(May%202026)-yellow?style=flat&labelColor=purple&color=yellow' alt='lsu' style='width: 50%;'>
                    <img  src='https://img.shields.io/badge/Computer%20Science%20(BS)-dee0e3' alt='major'>
                    <img  src='https://img.shields.io/badge/Concentration-Software%20Engineering-dee0e3' alt='concentration' style='width:50%;'>
                    <img  src='https://img.shields.io/badge/Presidents%20Honor%20Roll-dee0e3' alt='awards'>
                    <img  src='https://img.shields.io/badge/Cumulative%20GPA%3A4.02-dee0e3' alt='gpa'>
                  </div>
                </div>
                  <div class='tab-4'>
                    <label for='tab4-2'>Languages</label>
                    <input id='tab4-2' name='tabs' type='radio'>
                    <div>
                      <img  src='https://img.shields.io/badge/JavaScript-dee0e3?logo=JavaScript' alt='JS' style='width: 22%;'>
                      <img  src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' alt='css' style='width:16%;'>
                      <img  src='https://img.shields.io/badge/Java-dee0e3' alt='java' style='width:12%;'>
                      <img  src='https://img.shields.io/badge/Python-dee0e3?logo=python' alt='python' style='width:20%;'>
                      <img  src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' alt='html' style='width:18%;'>
                      <img src='https://img.shields.io/badge/SQL-dee0e3?logo=mysql' alt='sql' style='width:16%;'>
                      <img src='https://img.shields.io/badge/Dhall-dee0e3?logo=dhall' alt='dhall' style='width:14%;'>
                    </div>
                  </div>
                  <div class='tab-4'>
                    <label for='tab4-3'>Frameworks</label>
                    <input id='tab4-3' name='tabs' type='radio'>
                    <div>
                      <img src='https://img.shields.io/badge/Kubernetes-dee0e3?logo=kubernetes' alt='kubernetes' style='width:25%;'>
                      <img src='https://img.shields.io/badge/Svelte-dee0e3?logo=Svelte' alt='svelte' style='width:19%'>
                      <img src='https://img.shields.io/badge/React-dee0e3?logo=React' alt='react' style='width:19%'>
                      <img src='https://img.shields.io/badge/Flask-dee0e3?logo=Flask' alt='flask' style='width:19%'>
                      <img src='https://img.shields.io/badge/Bootstrap-dee0e3?logo=Bootstrap' alt='bootstrap' style='width:23%'>
                      <img src='https://img.shields.io/badge/AlpineJS-dee0e3?logo=Alpine.JS' alt='alpine' style='width: 22%'>
                    </div>
                  </div>
                  <div class='tab-4'>
                    <label for='tab4-4'>Technologies</label>
                    <input id='tab4-4' name='tabs' type='radio'>
                    <div>
                      <img src='https://img.shields.io/badge/Github-dee0e3?logo=github' alt='github' style='width: 20%;'>
                      <img src='https://img.shields.io/badge/AWS-dee0e3?logo=Amazon%20Web%20Services&logoColor=orange' alt='aws' style='width: 17%;'>
                      <img src='https://img.shields.io/badge/Linux-dee0e3?logo=Linux&logoColor=black' alt='linux' style='width: 19%;'>
                      <img src='https://img.shields.io/badge/Gitea-dee0e3?logo=Gitea' alt='gitea' style='width: 19%;'>
                      <img src='https://img.shields.io/badge/Bootstrap-dee0e3?logo=Bootstrap' alt='bootstrap' style='width: 24%;'>
                      <img src='https://img.shields.io/badge/GCP-dee0e3?logo=Google-cloud&logoColor=green' alt='gcp' style='width: 17%;'>
                      <img src='https://img.shields.io/badge/Kubernetes-dee0e3?logo=Kubernetes' alt='kubernetes' style='width: 26%;'>
                      <img src='https://img.shields.io/badge/Git-dee0e3?logo=Git' alt='git' style='width: 15%;'>
                      <img src='https://img.shields.io/badge/Docker-dee0e3?logo=Docker' alt='docker' style='width: 20%;'>
                      <img src='https://img.shields.io/badge/NodeJS-dee0e3?logo=Node.js' alt='nodejs' style='width: 20%;'>
                    </div>
                  </div>
                </div>
              </article>
          </div>
        </div>
      </div>
    </section> 
    <!--ABOUT-->
    <!--EXPERIENCE-->
    <section id='experience' class='full-height px-lg-5'>
      <div class='container'>
        <div class='row'>
          <div>
            <h6 class='header-text'>EXPERIENCE</h6>
              <h1>My Experience:</h1>
              <div class='display'>
                <div class='article-container'>    
                  <div>
                    <article class='project-card d-flex flex-column flex-md-row align-items-center' style='padding: 16px;'>
                      <div class='left-article col-12 col-md-6' style='font-weight: 700;'>
                        <div class="row" style='padding: 0; margin: 0;'>
                          <div class="col-6 text-start">
                            <h3>Brbytes</h3>
                          </div>
                          <div class="col-6 text-end">
                            <p>Baton Rouge, LA</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-6 text-start">
                            <p>Student Web Developer</p>
                          </div>
                          <div class="col-6 text-end">
                            <p>May 2024 - Present</p>
                          </div>
                          <div>
                            <img alt='HTML' src='https://img.shields.io/badge/HTML-dee0e3?logo=html5' style='width: 40px; height: 20px;' />
                            <img alt='CSS'  src='https://img.shields.io/badge/CSS-dee0e3?logo=css3&amp;logoColor=blue' style='width: 40px; height: 20px;' />
                            <img alt='JavaScript' src='https://img.shields.io/badge/JavaScript-dee0e3?logo=javascript' style='width: 60px; height: 20px;' />
                            <img alt='bootstrap' src='https://img.shields.io/badge/Bootstrap-dee0e3?logo=Bootstrap' style='width:14%'>
                            <img alt='alpine' src='https://img.shields.io/badge/AlpineJS-dee0e3?logo=Alpine.JS' style='width: 13%'>
                          </div>
                        </div>
                        <div style='text-align:left; margin:auto;'>
                          <p>•	Worked on the teacher’s portal for Brbytes’ new website to improve functionality and aesthetics</p>
                          <p>•	Collaborated with team members to achieve goals and merge changes made in git repos</p>
                          <p>•	Incorporated bootstrap tools to enhance the front-end design and leverage pre-built components</p>
                          <p>•	Fixed merge conflicts to ensure quality end product</p>
                          <p>•	Developed HTML essentials like navigation bar, dropdowns, logout logic, etc.</p>
                          <p>•	Debugged issues with bootstrap cards cutting off vertically, fixed by ensuring dynamic nature</p>
                        </div>
                      </div>
                      <div class='right-article col-12 col-md-6'>
                        <a href='https://www.brbytes.org/' target='_blank'><img class='article-img' src='brbytes.png' alt='brbytes' style=' border-radius: 25px;'/></a>
                      </div>
                    </article>
                  </div>  
                  <div>
                    <article class='project-card d-flex flex-column flex-md-row align-items-center'>
                      <div class='left-article col-12 col-md-6' style='font-weight: 700;'>
                        <div class="row" style='padding: 0; margin: 0;'>
                          <div class="col-6 text-start">
                        <header>Orca Security</header>
                        </div>
                        <div class="col-6 text-end">
                          <p>Baton Rouge, LA</p>
                        </div>           
                        </div> 
                        <div class="row">
                          <div class="col-6 text-start">
                            <p>Cloud Security Engineer Intern</p>
                          </div>
                          <div class="col-6 text-end">
                            <p>June 2024 - Present</p>
                          </div>         
                          </div>   
                        <div>
                          <img src='https://img.shields.io/badge/Kubernetes-dee0e3?logo=kubernetes' alt='kubernetes' style='width:18%;'>
                          <img src='https://img.shields.io/badge/AWS-dee0e3?logo=Amazon%20Web%20Services&logoColor=orange' alt='aws' style='width: 10%;'>
                          <img src='https://img.shields.io/badge/GCP-dee0e3?logo=Google-cloud&logoColor=green' alt='gcp' style='width: 10%;'>
                          <img src='https://img.shields.io/badge/Docker-dee0e3?logo=Docker' alt='docker' style='width: 14%;'>
                        </div>
                        <p>•	Learned the intricacies of the product to understand limitations and potential to benefit customers</p>
                        <p>•	Interacted with team members across the world to stay up to date with necessities and issues</p>
                        <p>•	Updated informative sheets to help co-workers stay up to date with new product updates and completed customer feature requests</p>
                        <p>•	Developed a two-node kubernetes cluster on GCP and implemented the informative dashboard</p>
                        <p>•	Looked into bugs of the product to open CFR requests</p>
                      </div>
                      <div class='right-article col-12 col-md-6'>
                        <a href='https://orca.security/' target='_blank'><img class='article-img' src='orca.png' alt='orca'/></a>
                      </div>
                    </article>
                    <h1 class='contact-me'>Get in Touch</h1>
                    <hr style='max-width:30%; margin-left: auto; margin-right: auto;'>
                    <h1 class='contact-me-2'>pngu123@lsu.edu</h1>
                    <div class='links'>
                    <a href='https://www.linkedin.com/in/peter-nguyen123/' target='_blank'>
                      <svg style='width: 4%; margin-left:45%; padding: 5px;'role="img" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin-in" class="svg-inline--fa fa-linkedin-in fa-2x" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                        <path fill="currentColor" d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69
                         37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z">
                        </path>
                      </svg>
                    </a>
                    <a href='https://github.com/peterN12g'>
                      <svg  style='width: 4%;' role="img" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="square-github" class="svg-inline--fa fa-square-github fa-2x" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                        <path fill="currentColor" d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z">
                        </path>
                      </svg>
                    </a>
                  </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>    
      <!--//EXPERIENCE-->
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
  /**Add left padding on larger screens*/
  #content-wrapper {
  padding-left: var(--sidbar-width);
  }
}
@media (max-width: 991.98px) {
  #content-wrapper {
    padding-left: 0;
    margin-left: 0;
    width: 100%;
  }
  #home {
    text-align: center;
  }
  #projects,#about,#experience {
    align-items: center;
  }
}
.navbar-brand img {
  border: 8px solid var(--color-body);
}
.home-img {
  width: 90%;
  margin-left: 5%;
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
.btn-brand:hover, .btn-brand:focus {
  background-color: var(--color-brand2);
  color: var(--color-base);
  border-color: var(--color-brand);
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
.tabs {
  display: flex;
  flex-wrap: wrap;
  margin: 0;
  overflow: hidden; 
}

.tabs [class^='tab'] label, .tabs [class*=' tab'] label {
  color: #efedef;
  cursor: pointer;
  display: block;
  font-size: 1.1em;
  font-weight: 300;
  line-height: 1em;
  padding: 2rem 0;
  text-align: center; 
}

.tabs [class^='tab'] [type='radio'], .tabs [class*=' tab'] [type='radio'] {
  border-bottom: 1px solid rgba(239, 237, 239, 0.5);
  cursor: pointer;
  appearance: none;
  display: block;
  width: 100%;
  transition: all 0.3s ease-in-out; 
}

.tabs [class^='tab'] [type='radio']:hover, .tabs [class*=' tab'] [type='radio']:hover, 
.tabs [class^='tab'] [type='radio']:focus, .tabs [class*=' tab'] [type='radio']:focus {
  border-bottom: 1px solid #fd264f; 
}

.tabs [class^='tab'] [type='radio']:checked, .tabs [class*=' tab'] [type='radio']:checked {
  border-bottom: 2px solid #fd264f; 
}

.tabs [class^='tab'] [type='radio']:checked + div, .tabs [class*=' tab'] [type='radio']:checked + div {
  opacity: 1; 
}

.tabs [class^='tab'] [type='radio'] + div, .tabs [class*=' tab'] [type='radio'] + div {
  display: block;
  opacity: 0;
  padding: 2rem 0;
  width: 100%;
  transition: all 0.3s ease-in-out; 
}

.tabs .tab-4 {
  width: 25%; 
}

.tabs .tab-4 [type='radio'] + div {
  width: 400%; 
  margin-left: 400%; 
}

.tabs .tab-4 [type='radio']:checked + div {
  margin-left: 0; 
}

.tabs .tab-4:nth-child(2) [type='radio'] + div {
  margin-left: -300%; 
}

.tabs .tab-4:nth-child(2) [type='radio']:checked + div {
  margin-left: -100%; 
}

.tabs .tab-4:nth-child(3) [type='radio'] + div {
  margin-left: -300%; 
}

.tabs .tab-4:nth-child(3) [type='radio']:checked + div {
  margin-left: -200%; 
}

.tabs .tab-4:nth-child(4) [type='radio'] + div {
  margin-left: -300%; 
}

.tabs .tab-4:nth-child(4) [type='radio']:checked + div {
  margin-left: -300%;
}
.tab-4 img {
  padding: 15px;
  width: 30%;
}
@media (max-width: 4000px) {

}
@media (max-width: 1245px) {
  .about_container {
    font-size: 0.8em;
  }
  #about_container_1 {
    font-size: 1rem;
  }
  .btn {
    margin-left: 1em;
  }
}
@media (max-width: 1090px) {
  .about_container {
    font-size: 0.6em;
  }
  #about_container_1 {
    font-size: 0.1rem;
  }
  .btn {
    margin-left: 1em;
  }
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
  /**Add left padding on larger screens*/
  #content-wrapper {
  padding-left: var(--sidbar-width);
  }
  .contact-me-2 {
    font-size: xx-large;
    color: var(--color-body);
    text-align: center;
  }
  .btn {
    margin-left: 1em;
  }
}
@media (max-width: 991.98px) {
  #content-wrapper {
    padding-left: 0;
    margin-left: 0;
    width: 100%;
  }
  #home {
    text-align: center;
  }
  #projects,#about,#experience {
    align-items: center;
  }
  .contact-me-2 {
    font-size: xx-large;
    color: var(--color-body);
    text-align: center;
  }
  .btn {
    margin-left: 1em;
  }
}
@media (max-width: 768px) {
  .about_container {
    font-size: 0.5em;
  }
}
@media (max-width: 488px) {
  .about_container {
    font-size: 0.4em;
  }
}
@media (max-width: 439px) {
  .intro-flex {
    display: flex;
    flex-direction: column;
  }
}

@media (max-width: 413px) {
  .about_container {
    font-size: 0.3em;
  }
}
.contact-me {
  text-align:center; 
  margin-top: 10px; 
  color: var(--color-body);
}
</style>