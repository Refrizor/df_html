# df_html
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>About DiamondFire</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
</head>

<style>
    body {
        color: black;
    }

    #bg {
        display: block;
        background-repeat: no-repeat;
        background-size: cover;
        background-position: bottom center, 50%, 50%;
        height: 1000px;
        background-image: url(bg1.png);
    }

    #information {
        font-size: 1rem;
        padding: 6px;
        border-radius: 10px;
    }

    #panel {
        /*        background: rgba(19, 19, 19, 0.98);*/
        background: rgba(233, 236, 239, 0.95);
        height: 1000px;
    }

    #subtitle {
        text-align: center;
        animation: slowFadeIn 0.5s;
    }

    #information {
        margin-left: auto;
        margin-right: auto;
        border-radius: 5px;
        background-color: white;
    }

    @keyframes fadeIn {
        from {
            opacity: 0%;
        }

        to {
            opacity: 100%;
        }
    }

    @keyframes slowFadeIn {
        0% {
            opacity: 0%;
        }

        50% {
            opacity: 0%;
        }

        100% {
            opacity: 100%;
        }
    }

    @keyframes domain {
        0% {
            color: black;
        }

        50% {
            color: slategray;
        }

        70% {
            color: darkorange;
        }

        100% {
            color: darkblue;
        }
    }

    @keyframes version {
        0% {
            background-color: #6C757D;
        }

        50% {
            background-color: #6C757D;
        }

        100% {
            background-color: darkorange;
        }
    }

    a {
        text-decoration: none;
        color: indianred;
    }

</style>

<body>

    <div id="bg">
        <div class="container" id="panel">

            <h1 class="display-4" style="text-align: center">About DiamondFire</h1>
            <p id="subtitle" class="lead">Join now at <b style="text-shadow: black 1px 1px 2px; animation: domain 4s, slowFadeIn 2s; animation-fill-mode: forwards" id="ip" onclick="copyAddress()" data-bs-toggle="tooltip" data-bs-placement="top" title="Click to copy!">mcdiamondfire.com</b></p>
            <hr style="color: gray">

            <div class="row row-cols-1 row-cols-md-2 g-3 mb-4">
                <div class="col">
                    <div class="card h-100 text-light bg-dark" style="animation: slowFadeIn 1s">
                        <div class="card-body">
                            <h5 class="card-title">Create your own minigames <span class="badge" style="animation: version 3s; animation-fill-mode: forwards">1.19+</span></h5>
                            <p class="card-text">At DiamondFire, you can create your very own minigames with a sequence of blocks without any prior programming experience.</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card h-100 text-light" style="background-color: cornflowerblue; animation: slowFadeIn 1.5s">
                        <div class="card-body">
                            <h5 class="card-title">Thousands of games available</h5>
                            <p class="card-text">There are thousands upon thousands of different playable minigames created by our community.</p>
                        </div>
                    </div>
                </div>
            </div>


            <div class="container mb-3" id="information" style="animation: fadeIn 2s">

                <p class="lh-sm">There's no need to set up a server or download any client mods, just join <b style="color: darkblue">DiamondFire</b> and get creating!</p>
                <hr style="color: gray">


                <p class="lh-sm">
                    In February 2016, DiamondFire was named the <a href="http://www.minecraftforum.net/news/60313-server-list-spotlight-top-5-mini-game-servers"><b>#1 Minigame Server</b></a> by the Minecraft Forum! Our server has consistently been praised for its unique concept, as well as its welcoming and collaborative community!
                </p>

                <p class="lh-sm">
                    In July 2017, DiamondFire was showcased at the <a href="https://www.youtube.com/watch?v=dOwVrUT8vck"><b>Scratch 2017 Conference</b></a> in Bordeaux, France! Scratch is a computer science education tool developed by MIT. By providing a block-based coding system directly within a Minecraft server, DiamondFire teaches programming concepts in a unique social environment; this results in high engagement and strong learning outcomes!
                </p>

                <p class="lh-sm">
                    In July 2020, DiamondFire was featured at <a href="https://www.youtube.com/watch?v=JB1RXvOJ-iw"><b>Snapcon 2020</b></a>, hosted by UC Berkeley! Many DiamondFire players have chosen to pursue fields such as computer science, game design, and animation.
                </p>

                <p class="lh-sm">
                    DiamondFire has also been featured by many amazing YouTubers from around the world! Check out the video below from CommandGeek.
                </p>

            </div>

            <div class="row">
                <div class="col-sm-6">
                    <div class="card" id="information" style="animation: slowFadeIn 2s">
                        <h5>DiamondFire Trailer</h5>
                        <iframe src="https://www.youtube.com/embed/SnahMFEgvRI" width="100%" height="300" class="mb-5"></iframe>
                    </div>
                </div>
                <div class="col-sm-6">
                    <div class="card" id="information" style="animation: slowFadeIn 2s">
                        <h5>Showcase by CommandGeek</h5>
                        <iframe src="https://www.youtube.com/embed/8c80719oWc8" width="100%" height="300" class="mb-5"></iframe>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>

    <script>
        function copyAddress() {
            /* Get the text field */


            /* Copy the text inside the text field */
            navigator.clipboard.writeText("mcdiamondfire.com");
        }

    </script>
</body>

</html>
