<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Atheria</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: black;
      color: white;
    }

    /* NAVBAR */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: rgba(0,0,0,0.8);
      position: fixed;
      width: 100%;
    }

    nav h1 {
      color: purple;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
    }

    /* HERO */
    .hero {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      background: linear-gradient(black, purple);
    }

    .hero h2 {
      font-size: 60px;
    }

    .hero p {
      margin: 20px 0;
      font-size: 20px;
    }

    .btn {
      background: purple;
      padding: 15px 30px;
      border-radius: 10px;
      text-decoration: none;
      color: white;
      font-size: 18px;
      transition: 0.3s;
    }

    .btn:hover {
      background: pink;
    }

    /* SECTION */
    .section {
      padding: 80px 20px;
      text-align: center;
    }

    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
      flex-wrap: wrap;
    }

    .card {
      background: #111;
      padding: 20px;
      border-radius: 15px;
      width: 250px;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav>
    <h1>Atheria</h1>
    <div>
      <a href="#">Accueil</a>
      <a href="#">Serveur</a>
      <a href="#">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <h2>Atheria</h2>
    <p>Le meilleur serveur Minecraft 🔥</p>
    <a class="btn" href="https://discord.gg/8qUWtdNarc" target="_blank">
      Rejoindre le Discord
    </a>
  </section>

  <!-- SECTION FEATURES -->
  <section class="section">
    <h2>Pourquoi nous rejoindre ?</h2>

    <div class="cards">
      <div class="card">
        <h3>⚔️ PvP</h3>
        <p>Affronte les meilleurs joueurs</p>
      </div>

      <div class="card">
        <h3>🏰 Faction</h3>
        <p>Crée ton empire</p>
      </div>

      <div class="card">
        <h3>💎 Économie</h3>
        <p>Deviens riche sur Atheria</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2026 Atheria - Tous droits réservés
  </footer>

</body>
</html>
