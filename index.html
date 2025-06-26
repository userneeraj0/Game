<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Don't Tap the Wrong Tile</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background: black;
      font-family: sans-serif;
    }
    #game {
      display: flex;
      flex-direction: column;
      height: 100vh;
    }
    .row {
      flex: 1;
      display: flex;
    }
    .tile {
      flex: 1;
      background: white;
      border: 1px solid #000;
    }
    .tile.active {
      background: black;
    }
    h2 {
      color: white;
      text-align: center;
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <h2>Score: <span id="score">0</span></h2>
  <div id="game"></div>

  <script>
    const game = document.getElementById("game");
    const scoreDisplay = document.getElementById("score");
    let score = 0;

    function createRow() {
      const row = document.createElement("div");
      row.classList.add("row");

      const activeIndex = Math.floor(Math.random() * 4);
      for (let i = 0; i < 4; i++) {
        const tile = document.createElement("div");
        tile.classList.add("tile");

        if (i === activeIndex) {
          tile.classList.add("active");
          tile.onclick = () => {
            score++;
            scoreDisplay.textContent = score;
            game.removeChild(row);
            game.appendChild(createRow());
          };
        } else {
          tile.onclick = () => {
            alert("❌ Game Over! Your Score: " + score);
            location.reload();
          };
        }

        row.appendChild(tile);
      }

      return row;
    }

    for (let i = 0; i < 4; i++) {
      game.appendChild(createRow());
    }
  </script>
</body>
</html>
