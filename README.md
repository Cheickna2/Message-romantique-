# Message-romantique-
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pour toi, madame Badji</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9f3f3;
            color: #4e4b5b;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            animation: fadeIn 2s ease-in;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            animation: fadeInText 3s ease-in-out;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 30px;
            animation: fadeInText 4s ease-in-out;
        }

        .button {
            background-color: #f28d8d;
            border: none;
            color: white;
            padding: 15px 30px;
            font-size: 1.5rem;
            cursor: pointer;
            border-radius: 30px;
            transition: background-color 0.3s ease;
            animation: fadeInText 5s ease-in-out;
        }

        .button:hover {
            background-color: #d75c5c;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes fadeInText {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

    </style>
</head>
<body>
    <div>
        <h1>Ma chère Badji,</h1>
        <p>
            Ce matin, je me suis réveillé en pensant à toi… Comme toujours.<br>
            Tu n’es pas encore réveillée, mais je voulais être le premier à te souhaiter une magnifique journée.<br>
            Je t’aime de tout mon cœur, profondément, sincèrement.<br>
            Tu es l’amour de ma vie, ma raison de sourire, mon bonheur au quotidien.<br>
            Quand tu liras ce message, j’espère que tu sentiras tout l’amour que j’ai pour toi.<br>
            Passe une merveilleuse journée, mon amour. Je suis là, à penser à toi, comme toujours.<br>
            Ton partenaire qui t’aime plus que tout.
        </p>
        <button class="button" onclick="window.location.href='messages.html'">Clique ici pour découvrir les messages de ton partenaire Cheick</button>
    </div>
</body>
</html>
