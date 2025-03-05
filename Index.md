<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Multi-Tool Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <div class="logo">MultiTool</div>
      <ul class="nav-links">
        <li><a href="/">Home</a></li>
        <li><a href="/tools">Tools</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
      <div class="hamburger">&#9776;</div>
    </nav>
  </header>

  <main>
    <!-- Homepage Section -->
    <section id="home">
      <h1>Welcome to MultiTool</h1>
      <p>Your one-stop solution for all online tools.</p>
      <a href="/tools" class="cta-button">Explore Tools</a>
    </section>

    <!-- Tool Listing Section -->
    <section id="tools">
      <h2>Our Tools</h2>
      <div class="tool-grid">
        <div class="tool-card">
          <h3>Tool 1</h3>
          <p>Description of Tool 1.</p>
          <a href="/tool-1">Learn More</a>
        </div>
        <!-- Repeat for other tools -->
      </div>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Us</h2>
      <p>We provide innovative tools to simplify your work.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <form>
        <input type="text" placeholder="Name" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 MultiTool. All rights reserved.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>