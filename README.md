<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hulstrike – Brick Breaker Game</title>
  <meta name="description" content="Hulstrike is a modern brick breaker game with fast-paced action, special power balls, and ancient-themed visuals." />
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: radial-gradient(circle at top, #1b1b1b, #000);
      color: #f0f0f0;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }

    .container {
      max-width: 720px;
      padding: 32px;
      text-align: center;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 16px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
    }

    h1 {
      font-size: 2.6rem;
      margin-bottom: 12px;
      letter-spacing: 1px;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 28px;
      color: #d0d0d0;
    }

    .buttons {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .store-link {
      display: block;
      padding: 16px 20px;
      border-radius: 12px;
      text-decoration: none;
      font-size: 1.1rem;
      font-weight: bold;
      transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease;
    }

    .store-link:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
    }

    .google {
      background: linear-gradient(135deg, #34a853, #1aa260);
      color: #fff;
    }

    .amazon {
      background: linear-gradient(135deg, #ff9900, #ffb347);
      color: #000;
    }

    footer {
      margin-top: 32px;
      font-size: 0.9rem;
      color: #999;
    }

    @media (min-width: 600px) {
      .buttons {
        flex-direction: row;
        justify-content: center;
      }

      .store-link {
        min-width: 260px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hulstrike</h1>
    <p>
      Hulstrike is a modern take on the classic brick breaker genre.
      Smash through ancient stone blocks, unlock powerful special balls,
      and progress through increasingly challenging levels.
      Simple to play, hard to master.
    </p>

    <div class="buttons">
      <a
        class="store-link google"
        href="https://play.google.com/store/apps/details?id=com.mikaka.hyperblock"
        target="_blank"
        rel="noopener"
      >
        Get it on Google Play
      </a>

      <a
        class="store-link amazon"
        href="https://www.amazon.com/gp/product/B0G2MWZG6G"
        target="_blank"
        rel="noopener"
      >
        Get it on Amazon Appstore
      </a>
    </div>

    <footer>
      © 2026 Hulstrike · Brick Breaker Game
    </footer>
  </div>
</body>
</html>

