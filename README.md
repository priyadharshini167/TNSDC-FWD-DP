<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Baking Bliss</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fff8f0;
      color: #333;
    }
    header, section, footer {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    header {
      background-color: #f7c59f;
      color: #fff;
      text-align: center;
    }
    nav a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    h2 {
      color: #d17a22;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      margin: 10px 0;
      padding: 10px;
      font-size: 1em;
    }
    button {
      background: #d17a22;
      color: white;
      border: none;
      padding: 10px;
      cursor: pointer;
    }
    button:hover {
      background: #a85e18;
    }

    /* ✅ Profile Styling */
    .profile {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #f7c59f;
    }
    .profile-info {
      flex: 1;
      min-width: 250px;
    }
    .profile-info h2 {
      margin-top: 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>Baking Bliss</h1>
    <p>Sweet Treats & Creative Recipes</p>
    <nav>
      <a href="#profile">Profile</a>
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- ✅ Profile Section -->
  <section id="profile">
    <div class="profile">
      <img src="profile.jpg" alt="priyadharshini Profile Picture" />
      <div class="profile-info">
        <h2>Hello! I'm priyadharshini</h2>
        <p>I’m a self-taught baker and dessert enthusiast with a big dream: to bring homemade goodness to kitchens everywhere.

  I’m styling cookies, testing new cake recipes, or blogging about the art of baking.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm priyadharshini, a passionate home baker who turned a hobby into a full-time journey of flour, frosting, and flavor. 

I specialize in creating handcrafted baking products using natural, wholesome ingredients.</p>
    <p>Whether it's sourdough bread, gluten-free muffins, or custom cake mixes — my goal is to make baking at home fun, easy, and delicious.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li><strong>DIY Cake Mix Kits:</strong> Just add eggs and milk! Perfect for quick, delicious treats at home.</li>
      <li><strong>Seasonal Cookie Boxes:</strong> Limited edition holiday treats made with love.</li>
      <li><strong>Recipe Blog:</strong> Sharing baking tutorials, tips, and fun decorating ideas weekly.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form action="mailto:your@email.com" method="post" enctype="text/plain">
      <label>Name:</label>
      <input type="text" name="name" required />

      <label>Email:</label>
      <input type="email" name="email" required />

      <label>Message:</label>
      <textarea name="message" rows="5" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Baking Bliss | Made with ❤️ and butter</p>
  </footer>

</body>
</html>
