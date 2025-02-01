<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ancient Civilizations</title>
  <link rel="stylesheet" href="">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f8f8;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }
    header {
      background-color: #fff;
      color: #333;
      padding: 20px 0;
      text-align: center;
      width: 100%;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      font-weight: 700;
    }
    .hero {
      background-image: url("https://images.app.goo.gl/3UtXY7ZHNGxiYnLp7");
      background-size: cover;
      background-position: center;
      color: #fff;
      padding: 150px 0;
      text-align: center;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;
    }
    .hero::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: -1;
    }
    .hero h2 {
      font-size: 3em;
      margin-bottom: 20px;
      font-weight: 700;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
    .hero p {
      font-size: 1.2em;
      line-height: 1.6;
      max-width: 600px;
      margin-bottom: 30px;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
    }
    .button {
      background-color: #f08080;
      color: #fff;
      padding: 15px 30px;
      border: none;
      border-radius: 5px;
      font-size: 1.1em;
      cursor: pointer;
      transition: background-color 0.3s ease;
      box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
    }
    .button:hover {
      background-color: #dc143c;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 50px;
      width: 100%;
    }
    .feature {
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      text-align: center;
      position: relative;
      overflow: hidden;
      transition: transform 0.3s ease;
    }
    .feature:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
    }
    .feature h3 {
      margin-top: 0;
      margin-bottom: 10px;
      font-weight: 700;
      position: relative;
      z-index: 1;
      color: #f08080;
    }
    .feature::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: #f8f8f8;
      z-index: -1;
      transform: translateX(-100%);
      transition: transform 0.5s ease;
    }
    .feature:hover::before {
      transform: translateX(0);
    }
    footer {
      background-color: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
      width: 100%;
    }
    @media (max-width: 768px) {
      .hero {
        padding: 50px 0;
      }
      .features {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Ancient Civilizations</h1>
  </header>
  <div class="hero">
    <h2>Explore the Wonders of Ancient Egypt, Greece, and Rome</h2>
    <p>Uncover the mysteries and legacies of these fascinating civilizations.  Sign up to download our exclusive resources and delve deeper into history.</p>
    <button class="button">Sign Up Now</button>
  </div>
  <div class="features">
    <div class="feature">
      <h3>Egypt</h3>
      <p>Discover the pyramids, hieroglyphics, and pharaohs of ancient Egypt.</p>
    </div>
    <div class="feature">
      <h3>Greece</h3>
      <p>Explore the birthplace of democracy, philosophy, and art.</p>
    </div>
    <div class="feature">
      <h3>Rome</h3>
      <p>Uncover the legacy of the Roman Empire, known for its vast territory and engineering feats.</p>
    </div>
  </div>
  <footer>
    <p>&copy; 2025 Ancient Civilizations</p>
  </footer>
</body>
</html>
