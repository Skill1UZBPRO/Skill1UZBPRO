<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SKIll1UZBPRO</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #222;
      padding: 1rem;
      font-size: 2rem;
      font-weight: bold;
      color: #00ffcc;
    }
    main {
      padding: 2rem;
    }
    a.game-link {
      display: block;
      margin: 1rem 0;
      padding: 1rem;
      background-color: #333;
      border-radius: 10px;
      color: #00ffcc;
      text-decoration: none;
      transition: background 0.3s;
    }
    a.game-link:hover {
      background-color: #444;
    }
  </style>
</head>
<body>

<header>SKIll1UZBPRO</header>

<main id="gameList" style="display: none;">
  <h2>Choose a Game:</h2>

  <a class="game-link" href="https://www.crazygames.com" target="_blank">CrazyGames</a>
  <a class="game-link" href="https://www.poki.com" target="_blank">Poki</a>
  <a class="game-link" href="https://www.y8.com" target="_blank">Y8 Games</a>
  <a class="game-link" href="https://www.kizi.com" target="_blank">Kizi</a>
  <a class="game-link" href="https://www.miniclip.com/games/en/" target="_blank">Miniclip</a>
  <a class="game-link" href="https://www.armorgames.com" target="_blank">Armor Games</a>
  <a class="game-link" href="https://www.agame.com" target="_blank">Agame</a>
  <a class="game-link" href="https://www.friv.com" target="_blank">Friv</a>
</main>

<script>
  const password = "Mironshoh";
  const userInput = prompt("Enter the secret code to access SKIll1UZBPRO:");

  if (userInput === password) {
    document.getElementById("gameList").style.display = "block";
  } else {
    document.body.innerHTML = "<h2 style='color: red; margin-top: 20%;'>Access Denied ❌</h2>";
  }
</script>

</body>
</html>

