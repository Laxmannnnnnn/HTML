<!DOCTYPE html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming Enthusiast Portfolio</title>
</head>
<body>

<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="portfolio.html">Portfolio</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>

<header>
  <h1>Gaming Portfolio by Laxman Bhattarai</h1>
</header>

<main>
  <section>
    <h2>About Me</h2>
    <p>I'm Laxman Bhattarai, a total gaming buff with a big dream: I want to become a game developer! I've been hooked on video games since I was a kid. There's something about diving into those virtual worlds and getting lost in the stories that get me going. I've spent countless hours playing games, but I'm not just about the playing—I'm also super curious about how these games are made. So, I've been diving into the world of game development, learning as much as I can so that one day, I can create my own games. For me, it's not just about landing a job—it's about turning my passion into a career where I can share the joy of gaming with others</p>
    <p><strong>My goal is to become a skilled game developer and create my own games that bring joy to players worldwide.</strong></p>
  </section>

  <section>
    <h2>Portfolio</h2>
    <figure>
      <img src="https://images.hdqwalls.com/wallpapers/pubg-mobile-z1.jpg" alt="Game 1" width="300" height="200">
      <figcaption>Game 1: Description of PUBG</figcaption>
      <p>PUBG (PlayerUnknown's Battlegrounds) is an online multiplayer battle royale game developed and published by PUBG Corporation. It is available on Microsoft Windows, MacOS, iOS, and Android platforms. In PUBG, players parachute onto a deserted island and must fight to be the last person or team standing by eliminating others while collecting weapons and gear. The game has gained immense popularity worldwide and has inspired several other battle royale games.</p>
    </figure>
    <figure>
      <img src="https://wallpapercave.com/wp/LcbfdJE.jpg" alt="Game 2" width="300" height="200">
      <figcaption>Game 2: Description of GOD OF WAR</figcaption>
      <p>God of War is a popular video game series developed by Santa Monica Studio and published by Sony Computer Entertainment. It follows the journey of the Greek god Kratos as he seeks redemption for his past sins. The first game in the series, God of War, was released in 2005 and was praised for its unique gameplay that combined action, adventure, and puzzle-solving elements with a captivating narrative. It has since become one of the most successful and critically acclaimed video game franchises.</p>

    </figure>
  </section>

  <section>
    <h2>Contact Me</h2>
    <form action="submit_message.php" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="4" required></textarea><br>
      <input type="submit" value="Submit">
    </form>
  </section>
</main>

</body>
</html>
