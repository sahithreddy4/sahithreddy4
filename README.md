<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hi, I'm John Doe, a web developer.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I have 5 years of experience in web development...</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="project">
      <img src="project1.jpg" alt="Project 1">
      <h3>Project 1</h3>
      <p>Description of Project 1</p>
    </div>
    <div class="project">
      <img src="project2.jpg" alt="Project 2">
      <h3>Project 2</h3>
      <p>Description of Project 2</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2023 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>

#css

/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Basic styles for the header and navigation */
header {
  background-color: #333;
  padding: 20px;
  color: #fff;
}

nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
}

/* Basic styles for the sections */
section {
  padding: 50px;
}

section h2 {
  margin-bottom: 20px;
}

/* Styles for the portfolio projects */
.project {
  margin-bottom: 30px;
}

.project img {
  max-width: 100%;
}

/* Basic styles for the contact form */
form input,
form textarea,
form button {
  display: block;
  width: 100%;
  margin-bottom: 10px;
}
