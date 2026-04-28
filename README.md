<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CréaNova</title>
    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background:linear-gradient(135deg,#0f0f0f,#1f1f1f);
            color:white;
        }

        section{
            min-height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            padding:40px 20px;
        }

        h1{
            font-size:4rem;
            margin-bottom:20px;
        }

        h2{
            font-size:2.5rem;
            margin-bottom:20px;
            color:#8b5cf6;
        }

        h3{
            font-size:1.8rem;
            margin-bottom:20px;
        }

        p{
            font-size:1.2rem;
            max-width:800px;
            margin-bottom:30px;
            line-height:1.7;
        }

        .btn{
            display:inline-block;
            padding:15px 35px;
            background:#8b5cf6;
            color:white;
            text-decoration:none;
            border-radius:10px;
            transition:0.3s;
            margin-top:15px;
        }

        .btn:hover{
            background:#a78bfa;
            transform:translateY(-3px);
        }

        .services{
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            gap:30px;
            margin-top:40px;
        }

        .card{
            background:#1e1e1e;
            padding:30px;
            width:320px;
            border-radius:20px;
            box-shadow:0 0 20px rgba(139,92,246,0.3);
            transition:0.3s;
        }

        .card:hover{
            transform:translateY(-10px);
        }

        .price{
            color:#8b5cf6;
            font-size:1.8rem;
            margin:20px 0;
            font-weight:bold;
        }

        html{
            scroll-behavior:smooth;
        }
    </style>
</head>
<body>

    <!-- Accueil -->
    <section id="home">
        <h1>CréaNova</h1>
        <p>
            Création de sites web, logos professionnels et montages vidéo
            pour entrepreneurs et petites entreprises.
        </p>
        <a href="#services" class="btn">Commencer</a>
    </section>

    <!-- Services -->
    <section id="services">
        <h2>Nos Services</h2>

        <div class="services">

            <!-- Site Web -->
            <div class="card">
                <h3>Création de Site Web</h3>
                <p>
                    Site moderne, rapide et professionnel pour développer
                    votre activité en ligne.
                </p>
                <div class="price">30€ - 50€</div>
                <p>
                    Modifications illimitées jusqu'à votre entière satisfaction.
                </p>
                <a href="mailto:contact@creanova.com?subject=Demande%20de%20création%20de%20site%20web&body=Bonjour%20CréaNova,%0A%0AJe%20souhaite%20obtenir%20plus%20d'informations%20concernant%20la%20création%20d'un%20site%20web.%0A%0AMerci." class="btn">
                    Nous contacter
                </a>
            </div>

            <!-- Logo -->
            <div class="card">
                <h3>Création de Logo</h3>
                <p>
                    Logo unique, professionnel et adapté à votre image de marque.
                </p>
                <div class="price">5€ - 10€</div>
                <p>
                    Modifications incluses jusqu'à satisfaction complète.
                </p>
                <a href="mailto:contact@creanova.com?subject=Demande%20de%20création%20de%20logo&body=Bonjour%20CréaNova,%0A%0AJe%20souhaite%20obtenir%20plus%20d'informations%20concernant%20la%20création%20d'un%20logo.%0A%0AMerci." class="btn">
                    Nous contacter
                </a>
            </div>

            <!-- Montage Vidéo -->
            <div class="card">
                <h3>Montage Vidéo</h3>
                <p>
                    Montage TikTok et YouTube Shorts professionnel.
                </p>
                <div class="price">
                    2 premiers montages gratuits
                </div>
                <p>
                    Puis abonnement de 9,99€/mois pendant 3 mois.
                </p>
                <a href="mailto:contact@creanova.com?subject=Demande%20de%20montage%20vidéo&body=Bonjour%20CréaNova,%0A%0AJe%20souhaite%20obtenir%20plus%20d'informations%20concernant%20vos%20services%20de%20montage%20vidéo.%0A%0AMerci." class="btn">
                    Nous contacter
                </a>
            </div>

        </div>
    </section>

</body>
</html>
