# Wolf2300.github.io
We are committed to provide you the most hygienic food in Delhi NCR
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ProTrade - Professional Trading Platform</title>
  <style>
    /* Base Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: #ffffff;
      background: #141e30; /* Fallback for older browsers */
      background: -webkit-linear-gradient(to right, #243b55, #141e30);
      background: linear-gradient(to right, #243b55, #141e30);
      transition: background 0.3s ease-in-out;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
    }

    /* Navigation Styles */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 0;
    }

    .navbar a {
      text-decoration: none;
      color: #ffffff;
      margin: 0 1rem;
      transition: color 0.3s;
    }

    .navbar a:hover {
      color: #ff7b00;
    }

    /* Section Styles */
    .section {
      min-height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 2rem 0;
      background-size: cover;
    }

    .section h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      text-transform: uppercase;
    }

    .section p {
      font-size: 1.2rem;
      max-width: 600px;
      text-align: center;
      margin-bottom: 2rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1rem 0;
      font-size: 0.9rem;
      background-color: #243b55;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar">
    <div class="container">
      <a href="#" onclick="navigateTo('home')">Home</a>
      <a href="#" onclick="navigateTo('features')">Features</a>
      <a href="#" onclick="navigateTo('pricing')">Pricing</a>
      <a href="#" onclick="navigateTo('contact')">Contact</a>
    </div>
  </nav>

  <!-- Dynamic Section -->
  <section id="dynamic-content" class="section">
    <!-- Content changes dynamically based on navigation -->
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2024 ProTrade - Your Partner in Professional Trading</p>
  </footer>

  <!-- JavaScript for Dynamic Content -->
  <script>
    const sections = {
      home: {
        title: "Welcome to ProTrade",
        content: "Trade smarter and achieve your financial goals with our state-of-the-art tools and resources. Start trading now!",
        background: "linear-gradient(to right, #243b55, #141e30)"
      },
      features: {
        title: "Features",
        content: "Explore powerful trading tools, real-time market data, and a range of analytical options designed for success.",
        background: "linear-gradient(to right, #0072ff, #00c6ff)"
      },
      pricing: {
        title: "Pricing Plans",
        content: "Choose from flexible plans to match your trading style and goals. We offer competitive and transparent pricing.",
        background: "linear-gradient(to right, #ff512f, #dd2476)"
      },
      contact: {
        title: "Contact Us",
        content: "Have questions or need support? Reach out to us, and we will be happy to assist you.",
        background: "linear-gradient(to right, #3a1c71, #d76d77, #ffaf7b)"
      }
    };

    function navigateTo(page) {
      const content = sections[page];
      if (content) {
        document.getElementById("dynamic-content").innerHTML = `
          <h1>${content.title}</h1>
          <p>${content.content}</p>
        `;
        document.body.style.background = content.background;
      }
    }

    // Load Home Page by Default
    navigateTo('home');
  </script>
</body>
</html>


