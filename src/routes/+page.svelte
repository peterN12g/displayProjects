<main>
    <div class="nav">
        <a href="/">Home</a>
        <a href="projects">My Projects</a>
        <a href="about">About Me</a>
    </div>
    <h1>
        Peter Nguyen | LSU | August 2022 - May 2026
    </h1>
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="lsu.png" alt="LSU Image" class="center">
</main>



<style>   
    h1{
        text-align: center;
    }
    .center{
        display: block;
        width: 40%;
        margin-left: auto;
        margin-right: auto;
    }
    .nav{
        overflow: hidden;
        background-color: black;
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
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
 
</style>