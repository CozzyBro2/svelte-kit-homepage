<style>
    * {
        margin: 0;
        padding: 0; 
        box-sizing: border-box;
        font-family: sans-serif;
    }

    :global(body) {
        height: 100vh;
        background-color: rgb(20, 20, 33);
    }

    .main {
        height: 800px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-size: large
    }

    .main h4 {
        font-size: 32px;
        color: white;
        font-weight: 600;
    }

    .main h4 span {
        color: orange;
        text-decoration: underline;
    }

    .main p.title {
        font-size: 44px;
        font-weight: 600;
        color: white;
        margin-top: 8px;
    }

    .main p.subtitle {
        font-size: 16px;
        color: #ccc;
        margin-top: 20px;
    }

    .logo {
        width: 250px;
        height: 250px;
        margin-top: 50px;
    }
</style>

<div class="main">
    <h4>Hi, I'm <span>HashCollision</span> 👋</h4>
    <p class="title">Developer, Hobbyist</p>
    <p class="subtitle">Slacking off since day one 👍</p>
    <enhanced:img class="logo" src="$lib/assets/logo.png" sizes="(min-width:270px)" alt = "My profile pic" />
</div>