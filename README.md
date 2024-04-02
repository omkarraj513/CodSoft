<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  
    <title>Omkar Landing Page</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>CodSoft Internship</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section class="hero">
      <h2>Welcome to our Product</h2>
      <p>Discover the amazing features that will revolutionize your life!</p>
      
      <a href="#" class="cta-button">Get Started</a>
    </section>

    <footer>
      <p>
        &copy; 2024 Rajput. All rights reserved.<br />
        Owner- Omkar Rajput<br />
        Web Development Internship ( Task 1)
      </p>
    </footer>
  </body>
</html>

*********************************************************************************

#CSS CODE

/* Reset some default browser styles */
body,
h1,
h2,
p,
ul,
li {
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
}

/* Header styles */
header {
  background-color: #333;
  color: #f5f1f1;
  padding: 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
}

nav li {
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: #faf8f8;
}

/* Hero section styles */
.hero {
  background-image: url("your-image.jpg");
  background-size: cover;
  text-align: center;
  padding: 140px 0;
  color: #090909;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
}

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #ff6600;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}

/* Footer styles */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
