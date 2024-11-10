# Wolf2300.github.io
We are committed to provide you the most hygienic food in Delhi NCR
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Professional Business Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>Your Business Name</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Hero Section -->
    <section id="hero">
      <h2>Welcome to Our Business</h2>
      <p>Delivering excellence in our services for over 10 years.</p>
      <button onclick="document.getElementById('contact').scrollIntoView()">Get in Touch</button>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Us</h2>
      <p>We are a professional team dedicated to providing top-notch services in our industry. Our mission is to help our clients succeed by delivering exceptional solutions.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
      <h2>Our Services</h2>
      <div class="service">
        <h3>Service 1</h3>
        <p>Description of Service 1.</p>
      </div>
      <div class="service">
        <h3>Service 2</h3>
        <p>Description of Service 2.</p>
      </div>
      <div class="service">
        <h3>Service 3</h3>
        <p>Description of Service 3.</p>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <form action="https://formspree.io/f/your-email" method="POST">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message</label>
        <textarea id="message" name="message" required></textarea>
        
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2023 Your Business Name. All rights reserved.</p>
  </footer>
</body>
</html>
