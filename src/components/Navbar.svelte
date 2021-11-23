<script>
    let menu = false;

    function toggleMenu() {
        menu = !menu;
    }
</script>

<nav>
    <img class="logo" src="img/logo.svg" alt="logo" />

    <ul>
        <li><a href="#">MENU</a></li>
        <li><a href="#">REWARDS</a></li>
        <li><a href="#">GIFT CARDS</a></li>
    </ul>

    <div class="user__actions">
        <div class="find__store">
            <img class="marker" src="img/marker.svg" alt="marker" />
            <p>Find a store</p>
        </div>

        <a href="#" class="btn btn__sign">Sign in</a>
        <a href="#" class="btn btn__join">Join now</a>
    </div>

    {#if !menu}
        <i on:click={toggleMenu} class="fas fa-bars menu" />
    {:else}
        <i on:click={toggleMenu} class="fas fa-times" />
    {/if}
</nav>

{#if menu}
    <div class="menu__mobile">
        <ul>
            <li><a href="#">MENU</a></li>
            <li><a href="#">REWARDS</a></li>
            <li><a href="#">GIFT CARDS</a></li>
        </ul>

        <div class="buttons">
            <a href="#" class="btn btn__sign">Sign in</a>
            <a href="#" class="btn btn__join">Join now</a>
        </div>

        <div class="mobile__find find__store">
            <img class="marker" src="img/marker.svg" alt="marker" />
            <p>Find a store</p>
        </div>
    </div>
{/if}

<style>
    nav {
        display: flex;
        align-items: center;
        font-size: 1.6rem;
        padding: 2rem 20rem;
        box-shadow: 0 1px 3px rgb(0 0 0 / 10%), 0 2px 2px rgb(0 0 0 / 6%),
            0 0 2px rgb(0 0 0 / 7%);
    }

    .fas {
        font-size: 2.5rem;
        cursor: pointer;
    }

    .menu {
        display: none;
    }

    nav .logo {
        width: 5rem;
        margin-right: 4rem;
    }

    nav ul {
        margin-right: auto;
        display: flex;
        gap: 2rem;
    }

    nav ul li a {
        color: #000;
        font-weight: 700;
    }

    .user__actions {
        display: flex;
        align-items: center;
        gap: 1.5rem;
    }

    .find__store {
        display: flex;
        align-items: center;
        gap: 1.5rem;
    }

    .find__store .marker {
        width: 2rem;
    }

    .find__store p {
        font-weight: bold;
    }

    .btn {
        border: 1px solid #000;
        padding: 0.7rem 1.6rem;
        border-radius: 50px;
    }

    .btn__sign {
        color: #000;
    }

    .btn__join {
        background: #000;
        color: #fff;
    }

    /* MOBILE */

    .menu__mobile {
        position: absolute;
        right: 0rem;
        background: #fff;
        width: 30rem;
        padding: 2rem;

        box-shadow: 0 1px 3px rgb(0 0 0 / 10%), 0 2px 2px rgb(0 0 0 / 6%),
            0 0 2px rgb(0 0 0 / 7%);
    }

    .menu__mobile ul {
        display: flex;
        flex-direction: column;
        gap: 1rem;
        font-size: 1.5rem;
        border-bottom: 1px solid #000;
    }

    .menu__mobile ul li {
        margin-bottom: 0.5rem;
    }

    .menu__mobile ul li a {
        color: #000;
    }

    .buttons {
        margin-top: 3rem;
        font-size: 1.6rem;
    }

    .mobile__find {
        margin-top: 3rem;
        font-size: 1.6rem;
    }

    @media only screen and (max-width: 1100px) {
        nav {
            justify-content: space-between;
            padding: 2rem 5rem;
        }

        nav ul {
            display: none;
        }

        .user__actions {
            display: none;
        }

        .menu {
            display: block;
        }
    }
</style>
