index.html//Mercedes.automobil.fr (Page d'accueil)


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mercedes automobil- Vente de voitures</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Mercedes automobil</h1>
            <p>Vente de voitures</p>
        </div>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#voitures">Nos Voitures</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#apropos">À propos</a></li>
            </ul>
        </nav>
    </header>

    <section id="accueil">
        <h2>Bienvenue sur notre site de vente de voitures</h2>
        <p>Nous vous proposons une large sélection de véhicules de qualité, à des prix compétitifs. Découvrez nos offres ci-dessous !</p>
    </section>

    <section id="voitures">
        <h2>Nos Voitures à Vendre</h2>
        <div class="car-list">
            <div class="car-item">
                <img src="car1.jpg" alt="Voiture 1">
                <h3>Ford Focus</h3>
                <p>Année: 2018 | Prix: 15 000 €</p>
                <p>Excellente voiture, faible kilométrage, idéale pour la ville.</p>
            </div>
            <div class="car-item">
                <img src="car2.jpg" alt="Voiture 2">
                <h3>Peugeot 208</h3>
                <p>Année: 2020 | Prix: 18 000 €</p>
                <p>Compacte et économique, parfaite pour un usage quotidien.</p>
            </div>
            <!-- Ajouter d'autres voitures -->
        </div>
    </section>

    <section id="contact">
        <h2>Contactez-nous</h2>
        <form action="mailto:Mercedes.auto@accountant.com" method="post" enctype="text/plain">
            <label for="name">Votre nom :</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Votre email :</label>
            <input type="email" id="email" name="email" required><br>

            <label for="message">Message :</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br>

            <button type="submit">Envoyer</button>
        </form>
    </section>

    <section id="apropos">
        <h2>À propos de Mercedes automobil</h2>
        <p>Frederic Savage est un expert en vente de voitures avec plus de 10 ans d'expérience. Nous nous engageons à fournir des véhicules de qualité à des prix compétitifs, avec un service client irréprochable.</p>
    </section>

    <footer>
        <p>&copy; 2025 Mercedes automobil Frédéric Savage - Tous droits réservés</p>
    </footer>
</body>
</html>
