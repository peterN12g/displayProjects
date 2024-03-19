<script>
    import './styles.css'
</script>

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
                <header>Warmup Calculator</header>
                <p>
                    A simple weightlifting warmup calculator to help lifters work up to their personal best attempt safely.
                    The calculator works seemlessly on mobile as a Progressive Web App (PWA) for user convenience.
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/warmupCalc" target="_blank">GitHub</a>
                    <a href="https://warmup.pages.dev/" target="_blank">Hosted Site</a>
                </footer>
            </article>
            <article>
                <header>GymShark Scraper</header>
                <p>
                    A python web scraper focused on GymShark products. When the price of specified products falls below a certain threshold,
                    an IOS push notification is sent. The site is hoted on AWS Lambda and uses CloudWatch to run the code every 30 minutes. 
                </p>
                <footer>
                    <a href="https://github.com/peterN12g/GymShark-Scraper" target="_blank">GitHub</a>
                    <a href="https://ibb.co/17tppmR" target="_blank">Example IOS Notification</a>
                </footer>
            </article>
            <article>
                <header>Nutrition Tracker</header>
                <p>
                    The nutrition tracker provides users the ability to calculate their basal metabolic rate (BMR) and lose weight with the calorie tracker.
                    Information about meals are API returned. Users have the ability to add specific foods, which then subtract the provided macronutrients from
                    their daily goals. 
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