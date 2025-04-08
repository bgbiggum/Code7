# Code7

body {
    font-family: sans-serif;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f4f4f4; /* Couleur de fond de la page */
}

.affiche {
    background-color: #000; /* Fond noir de l'affiche */
    color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
    text-align: center;
    width: 80%;
    max-width: 600px;
}

.titre {
    font-size: 2em;
    margin-bottom: 15px;
    color: #e50914; /* Rouge Netflix */
}

.image-container {
    position: relative;
    width: 100%;
    aspect-ratio: 16 / 9; /* Ratio d'un écran de télévision */
    background-color: #222; /* Fond sombre de l'écran */
    border-radius: 5px;
    overflow: hidden;
    margin-bottom: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.ecran {
    width: 90%;
    height: 90%;
    border: 2px solid #333;
    border-radius: 3px;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #111;
    overflow: hidden;
}

.logo-netflix {
    font-size: 2.5em;
    color: #e50914;
    font-weight: bold;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.8);
    z-index: 1; /* Assure que le logo est au-dessus de l'effet */
}

.telechargement-effect {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to right, rgba(255, 255, 255, 0.1) 0%, rgba(255, 255, 255, 0.3) 50%, rgba(255, 255, 255, 0.1) 100%);
    animation: glissement 2s linear infinite;
    background-size: 200% 100%;
    opacity: 0.5;
}

@keyframes glissement {
    0% { background-position: -100% 0; }
    100% { background-position: 100% 0; }
}

.sous-titre {
    font-style: italic;
    margin-bottom: 10px;
    color: #ccc;
}

.texte-principal {
    font-size: 1.2em;
    margin-bottom: 10px;
}

.texte-secondaire {
    font-style: italic;
    margin-bottom: 15px;
    color: #aaa;
}

.prix {
    font-size: 1.8em;
    font-weight: bold;
    color: #4CAF50; /* Couleur verte pour le prix */
    margin-bottom: 20px;
}

.contact {
    font-size: 1.1em;
    color: #fff;
    background-color: #e50914;
    padding: 10px 20px;
    border-radius: 5px;
    display: inline-block;
    text-decoration: none;
}
