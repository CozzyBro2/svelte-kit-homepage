<style>
    :global(body) {
        background-color: #0f0f12
    }

    * {
        margin: 0;
        padding: 0; 
        box-sizing: border-box;
        font-family: sans-serif;
    }

    @keyframes fadein {
        from {opacity: 0; transform: scale(0.95, 0.95)}
        to {opacity: 1; transform: scale(1.0, 1.0)}
    }

    .main {
        height: 800px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-size: large
    }

    .main p.subtitle {
        font-size: 16px;
        color: #ccc;
        margin-top: 20px;
        animation: fadein 2.1s;
    }
</style>

<div class="main">
    <p class="subtitle">Basically, i will be taking all of your data. Thanks you. 👍</p>
</div>