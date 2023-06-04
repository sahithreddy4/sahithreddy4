<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Personal Blog</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Personal Blog</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#blog">Blog</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="home">
    <h2>Welcome to My Blog!</h2>
    <p>Stay updated with my latest thoughts and ideas.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate writer and love to share my experiences...</p>
  </section>

  <section id="blog">
    <h2>Blog</h2>
    <article>
      <h3>My First Blog Post</h3>
      <p>Published on <time datetime="2023-06-04">June 4, 2023</time></p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    </article>
    <article>
      <h3>My Second Blog Post</h3>
      <p>Published on <time datetime="2023-06-05">June 5, 2023</time></p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    </article>
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
    <p>&copy; 2023 My Personal Blog. All rights reserved.</p>
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

/* Basic styles for the header */
header {
  background-color: #333;
  padding: 20px;
  color: #fff;
}

/* Basic styles for the navigation */
nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

/* Basic styles for the sections */
section {
  padding: 50px;
}

section h2 {
  margin-bottom: 20px;
}

/* Styles for the blog posts */
article {
  margin-bottom: 30px;
}

article h3 {
  margin-bottom: 10px;
}

/* Basic styles for the contact form */
form input,
form textarea,
form button {
  display: block;
  width: 100%;
  margin-bottom: 10px;
}
