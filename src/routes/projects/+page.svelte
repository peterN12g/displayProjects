<main>
    <div class="nav">
        <a href="/">Home</a>
        <a href="projects">My Projects</a>
        <a href="about">About Me</a>
    </div>
    <h1>
        My Projects:
    </h1>
    <div class='display'>
        <div class='article-container'>
            <article>
                <header>AniFinder</header>
                <p>
                    AniFinder is an AI powered Anime generator based on the user's preferences. The generator is powered by  google's AI, gemini pro.
                    The prompts include an anime genre and reference anime to generate a similar anime the user may enjoy.
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/anime" target="_blank">GitHub</a>
                    <a href="https://anifinder.pages.dev/" target="_blank">Hosted Site</a>
                </footer>
            </article>
            <article>
                <header>Warmup Calculator</header>
                <p>
                    A simple weightlifting warmup calculator to help lifters work up to their personal best attempt safely.
                    The calculator works seamlessly on mobile as a Progressive Web App (PWA) for user convenience.
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/warmupCalc" target="_blank">GitHub</a>
                    <a href="https://warmup.pages.dev/" target="_blank">Hosted Site</a>
                </footer>
            </article>
            <article>
                <header>GymShark Scraper</header>
                <p>
                    a Python-based web scraper focused on GymShark products. The server is hosted using Python Flask,
                    with Caddy used to reverse proxy over HTTPS. The backend Python server provides data via an API endpoint.
                    The frontend, built with React, displays the information on a webpage and includes a Progressive Web App
                    (PWA) that sends browser notifications through a service worker.  
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/GymShark-Scraper" target="_blank">GitHub</a>
                    <a href="https://gymshark-scraper.peternguyen.tech/" target="_blank">Hosted Site</a>
                    <a href="https://ibb.co/17tppmR" target="_blank">Example IOS Notification</a>
                </footer>
            </article>
            <article>
                <header>Nutrition Tracker</header>
                <p>
                    The nutrition tracker provides users the ability to calculate their basal metabolic rate (BMR) and lose weight with the calorie tracker. 
                    Information about meals is API returned. Users can add specific foods, which then subtract the provided macronutrients from their daily goals. 
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/nutritiontrack" target="_blank">GitHub</a>
                </footer>
            </article>
        </div>
    </div>
</main>

<style>
    .nav{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
        overflow: hidden;
        background-color: black;
    }
    .nav a{
        float: left;
        color: #f2f2f2;
        text-align: center;
        padding: 14px 200px;
        text-decoration: none;
        font-size: 17px;
    }
    .nav a:hover{
        background-color: #ddd;
        color: black;
    }
    h1{
        text-align: center;
    }

    .article-container{
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        justify-content: center;
    }
    article {
        flex: 0 1 600px;
        min-height: 200px;
        border-radius: 15px;
        padding: 20px;
        text-align: center;
        border: 1px solid black;
        display: flex;
        flex-direction: column;
        background-color: lightgray;
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
    }
    header{
        text-align: center;
    }
    a{
        padding: 15px;
    }
</style>