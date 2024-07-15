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
    <div class="flex-container">
        <div class="flex-child">
            <div>
        <h1>About me</h1>
        <p class = 'Intro'>
            I'm Peter, an aspiring Software Engineer at LSU. I graduate in May 2026 with a B.S in Computer Science. In my free time I powerlift
            with friends and program to relax my mind. I began programming with Java, though I've become accustomed to HTML/CSS, JavaScript,
            and Python, which is my current preferred coding language. That's it about me for now, take time to take a look at my resume or projects to see 
            what I've been working on.
        </p>
        <button class="button-28" on:click={openResume}>Resume</button>
    </div>
</div>
    <div class="flex-child">
    <div>
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="IMG_9245.jpg" alt="Personal Image" class="personal_img">
    </div>
</div>
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

    .button-28 {
        appearance: none;
        background-color: transparent;
        border: 2px solid #1A1A1A;
        border-radius: 15px;
        box-sizing: border-box;
        color: lightgray;
        cursor: pointer;
        display: inline-block;
        font-family: Roobert,-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
        font-size: 16px;
        font-weight: 600;
        line-height: normal;
        margin: 0;
        min-height: 60px;
        min-width: 0;
        outline: none;
        padding: 12px 18px;
        text-align: center;
        text-decoration: none;
        transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;
        width: 100%;
        will-change: transform;
        font: bold;
    } 
    .button-28:disabled { 
        pointer-events: none;
    }
    .button-28:hover {
        color: #fff;
        background-color: #1A1A1A;
        box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
        transform: translateY(-2px);
    } 
    .button-28:active {
        box-shadow: none; transform: translateY(0);
    }
    .flex-container {
    display: flex;
    }

    .flex-child {
        flex: 1;
    }  

    .flex-child:first-child {
        margin-right: 20px;
    } 
    .personal_img {
        width: 40%;
        margin-left: 30%;
    }
</style>