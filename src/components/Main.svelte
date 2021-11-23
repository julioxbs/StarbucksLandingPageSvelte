<script>
</script>

<section class="box box-a bg-primary">
    <div class="box-inner">
        <h2 class="text-xl">JINGLE ALL THE WAY TO FREE FAVORITES</h2>

        <p class="text-md">
            Join Starbucks® Rewards for delicious deals & exclusive offers.
        </p>

        <a href="#" class="btn">Learn more</a>
    </div>
</section>

<section class="box box-b bg-secondary grid-2">
    <img src="/img/box-b.png" alt="" />

    <div class="box-text">
        <h2 class="text-xl">NEW TO THE NICE LIST</h2>

        <p class="text-md">
            For a nondairy twist on a holiday cookie classic, try the new Iced
            Sugar Cookie Almondmilk Latte.
        </p>

        <a href="#" class="btn">Order now</a>
    </div>
</section>

<section class="box box-c grid-2 bg-secondary">
    <div class="box-text">
        <h2 class="text-xl">MERRY MOMENT</h2>

        <p class="text-md">
            Treat yourself to a festive Sugar Plum Cheese Danish with a nicely
            spiced sugar-plum spread.
        </p>

        <a href="#" class="btn">Order now</a>
    </div>

    <img src="/img/box-c.png" alt="" />
</section>

<section class="box box-d grid-2 bg-primary">
    <img src="/img/box-d.png" alt="" />

    <div class="box-text">
        <h2 class="text-xl">MERRY MOMENT</h2>

        <p class="text-md">
            Treat yourself to a festive Sugar Plum Cheese Danish with a nicely
            spiced sugar-plum spread.
        </p>

        <a href="#" class="btn">Order now</a>
    </div>
</section>

<section class="box box-e bg-secondary grid-2">
    <div class="box-text">
        <h2 class="text-xl">Fighting hunger this holiday</h2>

        <p class="text-md">
            Hunger is affecting millions of people across America this holiday
            season. Join us in our commitment to hunger relief and help feed
            neighbors in need.
        </p>

        <a href="#" class="btn">Order now</a>
    </div>

    <img src="/img/box-e.jpg" alt="" />
</section>

<section class="box-f grid-2">
    <div>
        <img src="/img/box-f1.jpg" alt="" />

        <div class="bg-extra extra">
            <div class="box-text">
                <h2 class="text-md">Let the holiday cheer come to you</h2>

                <p class="text-sm">
                    Make the moment merry. Order Starbucks® holiday favorites on Uber Eats.*
                </p>

                <a href="#" class="btn">Order now</a>
            </div>
        </div>
    </div>

    <div>
        <img src="/img/box-f2.jpg" alt="" />

        <div class="bg-extra bg-primary">
            <div class="box-text">
                <h2 class="text-md">Let the holiday cheer come to you</h2>

                <p class="text-sm">
                    Make the moment merry. Order Starbucks® holiday favorites on Uber Eats.*
                </p>

                <a href="#" class="btn">Order now</a>
            </div>
        </div>
    </div>
</section>

<hr>

<footer>
    <ul>
        <li class="icon"><a href="#"><img src="img/social-facebook.svg" alt=""></a></li>
        <li class="icon"><a href="#"><img src="img/social-instagram.svg" alt=""></a></li>
        <li class="icon"><a href="#"><img src="img/social-pinterest.svg" alt=""></a></li>
        <li class="icon"><a href="#"><img src="img/social-spotify.svg" alt=""></a></li>
        <li class="icon"><a href="#"><img src="img/social-twitter.svg" alt=""></a></li>
        <li class="icon"><a href="#"><img src="img/social-youtube.svg" alt=""></a></li>
    </ul>

    <p class="text-sm">© 2021 Starbucks Coffee Company. All rights reserved.</p>
</footer>

<style>
    a {
        color: #fff;
    }

    img {
        width: 100%;
    }

    section {
        margin-bottom: 2rem;
    }

    .btn {
        border: 1px solid #fff;
        padding: 1rem 2rem;
        border-radius: 10px;
    }

    .bg-primary {
        background: #006241;
    }

    .bg-secondary {
        background: #d50032;
    }

    .extra {
        background: #d4e9e2;
    }

    .box-a {
        padding: 4rem 0;
    }

    .grid-2 {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        justify-content: space-between;
        align-items: center;
        gap: 2rem;
    }

    .box-text {
        text-align: center;
        color: #fff;
        font-size: 1.6rem;
        max-width: 500px;
        justify-self: center;
    }

    .bg-extra {
        padding: 4rem 0;
    }

    .bg-extra .box-text {
        max-width: 100%;
        color: #000;
    }

    .box-inner {
        max-width: 70rem;
        margin: 0 auto;
        text-align: center;
        color: #fff;
        font-size: 2.4rem;
    }

    .text-xl {
        text-transform: uppercase;
        font-weight: 500;
        font-size: 5rem;
        letter-spacing: 6px;
        margin-bottom: 1.5rem;
    }

    .text-md {
        margin-bottom: 4rem;
        font-size: 2.4rem;
    }

    .text-sm {
        font-size: 1.4rem;
        margin-bottom: 2rem;
    }

    footer {
        padding: 2rem 1rem;
    }

    footer ul {
        display: flex;
        align-items: center;
        gap: 2rem;
        margin-bottom: 2rem;
    }

    footer ul .icon {
        width: 4rem;
    }

    @media only screen and (min-width: 1440px) {
        section {
            max-width: 144rem;
            margin: 0 auto;
            margin-bottom: 2rem;
        }
    }

    @media only screen and (max-width: 850px) {
        .text-xl {
            text-transform: uppercase;
            font-weight: 500;
            font-size: 3rem;
            letter-spacing: 6px;
            margin-bottom: 1.5rem;
        }

        .text-md {
            margin-bottom: 4rem;
            font-size: 1.4rem;
        }
    }

    @media only screen and (max-width: 800px) {
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr;
            justify-content: space-between;
            align-items: center;
            gap: 2rem;
        }

        .box-text {
            margin: 5rem 0;
        }
    }
</style>
