<style>

    :root {
        --header-color: purple;
        --nav-color: #d2691e;
        --footer-color: green;
    }

    header {
        background-color: var(--header-color);
        box-shadow: 0 3px 5px rgba(0, 0, 0, 0.4);
    }

    header > .logo {
        margin: 0;
        padding: 1vw;
        color: white;
    }

    nav {
        width: 100%;
        display: flex;
        justify-content: center;
    }

    nav > a {
        margin-top: 1vw;
        padding: 1vw 2vw;
        background: var(--nav-color);
        font-size: 2em;
        text-decoration: none;
        color: white; 
        border-radius: 2vw;
    }

    nav > a:not(:first-child) {
        margin-left: 5vw;
    }

    footer {
        position: fixed;
        width: 100vw;
        background-color: var(--footer-color);
        text-align: center;
        color: white;
        padding: 2vh 0;
        bottom: 0;
    }
</style>

<header><h1 class="logo">Idk Blog</h1></header>
<nav><a href="\">Posts</a><a href="">Placeholder 1</a><a href="">Placeholder 2</a></nav>
<slot />

<footer>PalaBeaveR ©</footer>
