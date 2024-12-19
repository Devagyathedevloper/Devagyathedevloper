<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming News</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">Gaming News</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#latest-news">Latest News</a></li>
        <li><a href="#reviews">Reviews</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="banner">
      <h1>Welcome to Gaming News</h1>
      <p>Your daily dose of gaming updates</p>
    </section>

    <section id="latest-news" class="news-section">
      <h2>Latest News</h2>
      <div class="news-container">
        <!-- Example news articles -->
        <article class="news-item">
          <img src="placeholder.jpg" alt="Game Image">
          <h3>Game Title 1</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Read More</a>
        </article>

        <article class="news-item">
          <img src="placeholder.jpg" alt="Game Image">
          <h3>Game Title 2</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Read More</a>
        </article>
      </div>
    </section>

    <section id="reviews">
      <h2>Game Reviews</h2>
      <p>Coming soon...</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Gaming News. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

 (styles.css)

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #121212;
  color: #ffffff;
}

header {
  background-color: #1f1f1f;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
}

header .logo {
  font-size: 24px;
  font-weight: bold;
}

header nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
}

header nav ul li a {
  color: #ffffff;
  text-decoration: none;
}

.banner {
  text-align: center;
  padding: 50px 20px;
  background-color: #282828;
}

.news-section {
  padding: 20px;
}

.news-container {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.news-item {
  background-color: #1f1f1f;
  padding: 15px;
  border-radius: 5px;
  width: 300px;
  text-align: center;
}

.news-item img {
  width: 100%;
  border-radius: 5px;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #1f1f1f;
}
 
 (script.js)

// JavaScript functionality can be added later for interactivity
console.log("Welcome to Gaming News!");
