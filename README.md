# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Blog - House Blogging</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #333;
      color: white;
      padding: 10px 0;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 0;
      margin: 0;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    main {
      padding: 20px;
      text-align: center;
    }

    .featured-image img {
      width: 100%;
      max-width: 600px;
      margin: 20px auto;
      display: block;
    }

    .blog-post img {
      width: 100%;
      max-width: 500px;
      margin: 10px auto;
      display: block;
    }

    .blog-posts .blog-post {
      margin-bottom: 40px;
    }

    .blog-posts .blog-post h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    .blog-posts .blog-post p {
      color: #555;
      font-size: 18px;
    }

    .blog-posts .blog-post a {
      color: #333;
      text-decoration: none;
      font-size: 18px;
      display: block;
      margin-top: 10px;
    }

    .blog-posts .blog-post a:hover {
      text-decoration: underline;
    }

    /* Pricing Table Styles */
    .pricing-table {
      display: flex;
      justify-content: center;
      margin-top: 30px;
    }

    .pricing-table .pricing-option {
      background-color: #fff;
      padding: 20px;
      margin: 10px;
      border-radius: 5px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
      width: 200px;
    }

    .pricing-table .pricing-option h3 {
      margin-top: 0;
    }

    .pricing-table .pricing-option .price {
      font-size: 24px;
      font-weight: bold;
      color: #333;
    }

    .pricing-table .pricing-option button {
      margin-top: 10px;
      padding: 10px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .pricing-table .pricing-option button:hover {
      background-color: #444;
    }

    /* Dark Mode Styles */
    body.dark-mode {
      background-color: #333;
      color: white;
    }

    body.dark-mode header, body.dark-mode footer {
      background-color: #222;
    }

    body.dark-mode button {
      background-color: #555;
    }

  </style>
</head>
<body>
  <header>
    <nav>
      <ul class="nav">
        <li><a href="#home">Home</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Home Page Content -->
    <section id="home" class="intro">
      <h1>Welcome to My Blog</h1>
      <p>Sharing ideas, tutorials, and more about houses and interior design.</p>
      <button onclick="changeTheme()">Toggle Theme</button>
    </section>

    <section class="featured-image">
      <img src="images/house.jpg" alt="Beautiful House" />
    </section>

    <!-- Blog Page Content -->
    <section id="blog" class="blog-posts">
      <h1>My Blog Posts</h1>
      <p>Read all about house design, interiors, and more!</p>

      <!-- Sample Blog Post 1 -->
      <article class="blog-post">
        <h2>10 Tips for Decorating Your Living Room</h2>
        <img src="images/interior1.jpg" alt="Living Room Interior" />
        <p>Learn how to decorate your living room with these 10 tips. From furniture to color schemes, we've got you covered!</p>
        <a href="#">Read More</a>
      </article>

      <!-- Sample Blog Post 2 -->
      <article class="blog-post">
        <h2>Renovating Your Kitchen on a Budget</h2>
        <img src="images/interior2.jpg" alt="Kitchen Interior" />
        <p>Renovating your kitchen doesn't have to break the bank. Here are budget-friendly ways to improve your kitchen's look and feel.</p>
        <a href="#">Read More</a>
      </article>

      <!-- Sample Blog Post 3 -->
      <article class="blog-post">
        <h2>How to Create a Cozy Bedroom</h2>
        <img src="images/interior3.jpg" alt="Bedroom Interior" />
        <p>Transform your bedroom into a cozy haven with these easy tips. Learn how lighting, color, and furniture make a difference.</p>
        <a href="#">Read More</a>
      </article>
    </section>

    <!-- Pricing Table for House Stay -->
    <section class="pricing-table">
      <h2>Stay With Us</h2>
      <div class="pricing-option">
        <h3>1 Night Stay</h3>
        <div class="price">$150</div>
        <button>Book Now</button>
      </div>
      <div class="pricing-option">
        <h3>1 Week Stay</h3>
        <div class="price">$900</div>
        <button>Book Now</button>
      </div>
      <div class="pricing-option">
        <h3>1 Month Stay</h3>
        <div class="price">$3000</div>
        <button>Book Now</button>
      </div>
    </section>
  </main>

  <footer id="about">
    <p>&copy; 2025 My Blog. All rights reserved.</p>
    <p>About Us: We provide blogging content focusing on house designs, home interiors, and real estate. Follow us for tips on how to design and maintain a beautiful home.</p>
  </footer>

  <script>
    // Toggle Dark Mode
    function changeTheme() {
      document.body.classList.toggle('dark-mode');
    }
  </script>
</body>
</html>

