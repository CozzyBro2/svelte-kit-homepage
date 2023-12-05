<style>
    * {
        margin: 0;
        padding: 0; 
        box-sizing: border-box;
        font-family: sans-serif;
    }

    :global(body) {
        background-color: #0f0f12
    }

    .main {
        height: 800px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-size: large
    }

    @keyframes fadein {
        from {opacity: 0; transform: scale(0.95, 0.95)}
        to {opacity: 1; transform: scale(1.0, 1.0)}
    }

    .main h4 {
        font-size: 32px;
        color: white;
        font-weight: 600;
        transition: transform 0.4s;
        animation: fadein 1.9s;
    }

    .logo:hover {
        transform: scale(1.2, 1.2);
    }
    .main h4 span {
        color: orange;
        text-decoration: underline;
        animation: fadein 1.9s;
    }

    .main p.title {
        font-size: 44px;
        font-weight: 600;
        color: white;
        margin-top: 8px;
        animation: fadein 2.0s;
    }

    .main p.subtitle {
        font-size: 16px;
        color: #ccc;
        margin-top: 20px;
        animation: fadein 2.1s;
    }

    .logo {
        width: 250px;
        height: 250px;
        margin-top: 50px;
        opacity: 1;
        transition: transform 0.33s;
        animation: fadein 2.2s;
    }
</style>

<div class="main">
    <h4>Hi, I'm <span>HashCollision</span> 👋</h4>
    <p class="title">Developer, Hobbyist</p>
    <p class="subtitle">Slacking off since day one 👍</p>

    <enhanced:img class="logo" src="$lib/assets/logo.png" sizes="min(270px, 100vw)" alt = "My profile pic" />
</div>