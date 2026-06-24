<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ma GitHub Page</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background: #1e293b;
      padding: 20px;
      text-align: center;
    }

    main {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      padding: 40px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2rem;
      opacity: 0.8;
      max-width: 600px;
      text-align: center;
    }

    a.button {
      margin-top: 20px;
      padding: 12px 20px;
      background: #3b82f6;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.2s;
    }

    a.button:hover {
      background: #2563eb;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #1e293b;
      font-size: 0.9rem;
      opacity: 0.8;
    }
  </style>
</head>

<body>
  <header>
    <h2>Mon site GitHub</h2>
  </header>

  <main>
    <h1>Bienvenue 👋</h1>
    <p>
      Ceci est une page web hébergée gratuitement avec GitHub Pages.
      Tu peux modifier ce texte, ajouter des sections, des images ou un portfolio.
    </p>

    <a class="button" href="https://github.com/" target="_blank">
      Voir GitHub
    </a>
  </main>

  <footer>
    © 2026 - Mon site
  </footer>
</body>
</html>
