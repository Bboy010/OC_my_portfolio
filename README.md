<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8" >
    <title>Accueil - Blackboy illustration</title>
    <link href="style/style.css" rel="stylesheet" >
    <link href="style/index.css" rel="stylesheet" >
    <link rel="preconnect" href="https://fonts.googleapis.com"> <!-- Insertion de police -->
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Manrope&family=Montserrat&display=swap" rel="stylesheet">
</head>

<body>
    <header>
        <nav>
            <img src="images/logo.png" alt="Logo Hongo Koffi Anderson">
            <div>
                <a href="index.html">Accueil</a>
                <a href="a-propos.html">À propos</a>
                <a href="portfolio.html">Portfolio</a>
            </div>
        </nav>
    </header>
    <main>
        <section class="accueil-introduction">
            <div>
                <h1>Blackboy illustration</h1>
                <p>
                    Où <em>professionalisme</em> s’allie avec <em>passion</em>. Depuis
                    plus de 5 ans maintenant, j’exerce mon métier avec la passion
                    qui m’anime : capturer l’essence de chaque instant.
                </p>
                <a href="#contact" class="cta">UN PROJET ? ÉCRIVEZ-MOI</a>
            </div>
            <img src="images/Blackboy0.png" alt="Portrait avec effet de la photographe Hongo Koffi Anderson" >
        </section>
        <section class="accueil-photos">
            <h2>Mon dernier projet</h2>
            <div>
                <img src="images/accueil/element-1.1.png" alt="Twelve apostles - Australie" >
                <img src="images/accueil/element-3.3.png" alt="Wai-O-Tapu - Nouvelle-Zélande" >
                <img src="images/accueil/element-2.2.png" alt="Parc National d’Abel Tasman - Nouvelle-Zélande" >
            </div>
            <div>
                <img src="images/accueil/element-4.4.png" alt="Lac Rotorua - Nouvelle-Zélande" >
                <img src="images/accueil/element-5.5.png" alt="Milford Sound - Nouvelle-Zélande" >
                <img src="images/accueil/element-6.6.png" alt="Lac Wanaka - Nouvelle-Zélande" >
            </div>
        </section>
        <section id="contact" class="section-contact">
            <h2>Parlons de votre projet</h2> <!-- Création de formulaire --> 
            <form method="get" action="#">
                <div class="form-nom-email">
                    <div class="form-column">
                        <label for="nom">nom</label>
                        <input type="text" name="nom" id="nom" >
                    </div>
                    <div class="form-column">
                        <label for="email">email</label>
                        <input type="email" name="email" id="email" >
                    </div>
                </div>
                <label for="message">message</label>
                <textarea name="message" id="message" rows="10"></textarea>
                <input type="submit" value="ENVOYER" class="cta" >
            </form>
        </section>
    </main>
    <footer>
        <img src="images/logo.png" alt="Logo Hongo Koffi Anderson" >
        <div>
            <a target="_blank" href="https://twitter.com/Blackboy_art" class="lien-icone">
                <img src="images/twitter.png" alt="Logo Twitter" >
            </a>
            <a target="_blank" href="https://www.instagram.com/bboy_art_officiel/" class="lien-icone">
                <img src="images/instagram.png" alt="Logo Instagram" >
            </a>
        </div>
    </footer>
  </body>
</html>
