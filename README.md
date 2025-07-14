# Test
Test
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simple Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #007BFF;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0 0 10px;
    }
    header p {
      margin: 0 0 20px;
    }
    .btn {
      background: white;
      color: #007BFF;
      padding: 10px 20px;
      border: none;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
    }
    section {
      padding: 2rem 1rem;
      max-width: 800px;
      margin: auto;
    }
    .about {
      background-color: #fff;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      margin-bottom: 2rem;
    }
    .contact form {
      display: flex;
      flex-direction: column;
    }
    .contact input,
    .contact textarea {
      margin-bottom: 1rem;
      padding: 0.75rem;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #eee;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Your Brand</h1>
    <p>We help you grow your business with smart technology</p>
    <button class="btn">Get Started</button>
  </header>

  <section class="about">
    <h2>About Us</h2>
    <p>
      We provide simple and scalable solutions for businesses and individuals. Our tools help automate work, reach more people, and grow faster.
    </p>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required/>
      <input type="email" placeholder="Your Email" required/>
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Your Brand. All rights reserved.
  </footer>

</body>
</html>
