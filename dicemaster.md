<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentation du Bot Discord</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin-top: 20px;
            background: #444;
            color: #fff;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        h1, h2, h3, h4 {
            color: #333;
        }
        code {
            background: #eee;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Documentation du Bot Discord</h1>
    </header>
    <div class="container">
        <nav>
            <a href="#introduction">Introduction</a>
            <a href="#installation">Installation</a>
            <a href="#commandes">Commandes</a>
            <a href="#faq">FAQ</a>
            <a href="#support">Support</a>
        </nav>
        
        <section id="introduction">
            <h2>Introduction</h2>
            <p><strong>NomDuBot</strong> est un bot Discord conçu pour [description détaillée de ce que fait le bot]. Il offre une gamme de fonctionnalités pour améliorer votre expérience sur Discord.</p>
        </section>

        <section id="installation">
            <h2>Installation</h2>
            <p>Pour ajouter <strong>NomDuBot</strong> à votre serveur Discord, suivez ces étapes :</p>
            <ol>
                <li>Cliquez sur <a href="#">ce lien d'invitation</a> pour ajouter le bot à votre serveur.</li>
                <li>Assurez-vous d'avoir les permissions nécessaires pour ajouter un bot.</li>
                <li>Suivez les instructions à l'écran pour autoriser le bot.</li>
            </ol>
            <p>Une fois ajouté, le bot sera opérationnel et prêt à utiliser les commandes décrites ci-dessous.</p>
        </section>

        <section id="commandes">
            <h2>Commandes</h2>

            <h3>Commandes de base</h3>

            <h4><code>!aide</code></h4>
            <p>Affiche la liste de toutes les commandes disponibles.</p>
            <pre><code>!aide</code></pre>

            <h4><code>!salut</code></h4>
            <p>Le bot répond avec un message de salutation.</p>
            <pre><code>!salut</code></pre>
            <p><strong>Exemple :</strong></p>
            <pre><code>Utilisateur : !salut
Bot : Bonjour ! Comment puis-je vous aider aujourd'hui ?</code></pre>

            <h3>Commandes avancées</h3>

            <h4><code>!ban &lt;utilisateur&gt; [raison]</code></h4>
            <p>Bannit un utilisateur du serveur.</p>
            <pre><code>!ban @utilisateur Comportement inapproprié</code></pre>
            <p><strong>Exemple :</strong></p>
            <pre><code>Utilisateur : !ban @Jean Comportement inapproprié
Bot : @Jean a été banni pour : Comportement inapproprié</code></pre>

            <h4><code>!mute &lt;utilisateur&gt; [durée]</code></h4>
            <p>Réduit un utilisateur au silence pour une durée spécifiée.</p>
            <pre><code>!mute @utilisateur 10m</code></pre>
            <p><strong>Exemple :</strong></p>
            <pre><code>Utilisateur : !mute @Paul 10m
Bot : @Paul a été mis en sourdine pour 10 minutes.</code></pre>
        </section>

        <section id="faq">
            <h2>FAQ</h2>
            <p><strong>Q : Comment puis-je inviter le bot sur mon serveur ?</strong><br>
            R : Utilisez <a href="#">ce lien d'invitation</a> et suivez les instructions.</p>

            <p><strong>Q : Que faire si une commande ne fonctionne pas ?</strong><br>
            R : Assurez-vous que le bot dispose des permissions nécessaires et que vous avez utilisé la commande correctement. Si le problème persiste, contactez le support.</p>
        </section>

        <section id="support">
            <h2>Support</h2>
            <p>Pour toute assistance supplémentaire, veuillez rejoindre notre <a href="#">serveur de support</a> ou nous contacter à <a href="mailto:support@nomdubot.com">support@nomdubot.com</a>.</p>
        </section>
    </div>
</body>
</html>
