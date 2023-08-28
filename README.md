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
        <nav style ="{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}">
            <img src="images/logo.png" alt="Logo Hongo Koffi Anderson">
            <div>
                <a href="index.html" style="{margin-left: 30px;}">Accueil</a>
                <a href="a-propos.html" style="{margin-left: 30px;}">À propos</a>
                <a href="portfolio.html" style="{margin-left: 30px;}">Portfolio</a>
            </div>
        </nav>
    </header>
    <main>
        <section style =" {  display: flex;  flex-direction: row;  width: 60%;  align-items: flex-start;  margin: auto;}" >
            <div style="{  padding-right: 80px; padding-right: 0;  text-align: center;  order: 2;}">
                <h1 style = "{  margin-bottom: 15px;}">Blackboy illustration</h1>
                <p style ="{  margin-bottom: 30px;}">
                    Où <em>professionalisme</em> s’allie avec <em>passion</em>. Depuis
                    plus de 5 ans maintenant, j’exerce mon métier avec la passion
                    qui m’anime : capturer l’essence de chaque instant.
                </p>
                <a href="#contact" class="cta">UN PROJET ? ÉCRIVEZ-MOI</a>
            </div>
            <img src="images/Blackboy0.png" alt="Portrait avec effet de la photographe Hongo Koffi Anderson" style ="{  order: 1;  margin-bottom: 20px;  width: 100%;}">
        </section>
        <section style ="{  background-color: white;  padding: 80px;}">
            <h2 style="{  color: #242424;  text-align: center;  margin-bottom: 80px;}">Mon dernier projet </h2>
            <div style ="{  display: flex;  flex-direction: row;  gap: 15px;  justify-content: center;  margin-bottom: 15px;}">
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
        <section id="contact" style ="{  color: #a5b4fc;  text-align: center;  margin-bottom: 50px; padding: 50px 20px;}"class="section-contact">
            <h2>Parlons de votre projet</h2> <!-- Création de formulaire --> 
            <form method="get" action="#" style ="{  display: flex;  flex-direction: column;  width: 40%;  margin: auto;  color: white;}">
                <div style ="{  display: flex;  flex-direction: row;  gap: 20px;flex-direction: column;  gap: 0; " class="form-nom-email">
                    <div style ="{  flex: 1;  display: flex;  flex-direction: column; margin-bottom: 20px;" class="form-column">
                        <label for="nom">nom</label>
                        <input type="text" name="nom" id="nom" style ="{  padding: 15px;  border-radius: 3px;  border: none;}">
                    </div>
                    <div class="form-column">
                        <label for="email" style ="{  margin-bottom: 10px;}">email</label>
                        <input type="email" name="email" id="email" >
                    </div>
                </div>
                <label for="message" style ="{  margin-bottom: 10px;}">message</label>
                <textarea name="message" id="message" rows="10" style ="{  padding: 15px;  border-radius: 3px;  border: none;}"></textarea>
                <input type="submit" value="ENVOYER" class="cta" style="input[type='submit'] {  width: 200px;  margin: auto;  margin-top: 30px;}">
            </form>
        </section>
    </main>
    <footer style ="{  display: flex;  flex-direction: row;  align-items: center;  justify-content: space-between;}">
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
