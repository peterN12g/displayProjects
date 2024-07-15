<script>
    function openResume(){
        window.open('Resume.pdf', '_blank')
    }
</script>

<main>
    <div class="nav">
        <a href="/">Home</a>
        <a href="projects">My Projects</a>
        <a href="about">About Me</a>
    </div>
    <div>
        <h1>About me</h1>
        <p class = 'Intro'>
            I'm Peter, an aspiring Software Engineer at LSU. I graduate in May 2026 with a B.S in Computer Science. In my free time I powerlift
            with friends. During this time I also relax and rest my mind. I began programming with Java, though I've become accustomed to HTML/CSS, JavaScript,
            and Python, which is my current preferred coding language. That's it about me for now, take time to take a look at my resume or projects!
        </p>
    </div>
    <div class="center">
        <button class='resume-button' on:click={openResume}>View my Resume</button>
    </div>
</main>

<style>
    .nav{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        width: auto;
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
    p{
        text-align: center;
        font-size: 1.5em;
    }
    .resume-button {
        border: none;
        padding: 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 20px;
        margin: 10px 5px;
        border-radius: 50%;
    }
    .center {
        margin: 0;
        position: absolute;
        top: 40%;
        left: 50%;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
</style>