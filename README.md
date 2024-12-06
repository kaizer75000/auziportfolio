<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Motion Design Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Motion Designer | Logo Animations | Motion Identities</p>
  </header>

  <main>
    <section id="portfolio">
      <h2>My Work</h2>
      <div class="video-grid">
        <!-- Video 1 -->
        <div class="video-card">
          <a href="https://www.youtube.com/watch?v=example1" target="_blank">
            <div class="thumbnail" style="background-image: url('thumbnail1.jpg');"></div>
          </a>
          <p>Project Title 1</p>
        </div>
        <!-- Video 2 -->
        <div class="video-card">
          <a href="https://www.youtube.com/watch?v=example2" target="_blank">
            <div class="thumbnail" style="background-image: url('thumbnail2.jpg');"></div>
          </a>
          <p>Project Title 2</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">yourprofile</a></p>
      <p>Instagram: <a href="https://instagram.com/yourprofile" target="_blank">@yourprofile</a></p>
    </section>
  </main>

  <footer>
    <p>© 2024 Your Name. All Rights Reserved.</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
  color: #333;
}

/* Header */
header {
  text-align: center;
  padding: 2rem;
  background-color: #333;
  color: white;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
}

header p {
  margin: 0.5rem 0 0;
  font-size: 1.2rem;
}

/* Portfolio Section */
#portfolio {
  padding: 2rem;
  text-align: center;
}

#portfolio h2 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  padding: 0 2rem;
}

.video-card {
  background: white;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  text-align: center;
  transition: transform 0.2s;
}

.video-card:hover {
  transform: scale(1.03);
}

.thumbnail {
  width: 100%;
  height: 200px;
  background-size: cover;
  background-position: center;
}

.video-card p {
  margin: 0;
  padding: 1rem;
  font-size: 1rem;
}

/* Contact Section */
#contact {
  padding: 2rem;
  text-align: center;
  background-color: #f4f4f9;
}

#contact h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

#contact p {
  font-size: 1rem;
  margin: 0.5rem 0;
}

#contact a {
  color: #007bff;
  text-decoration: none;
}

#contact a:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: white;
  font-size: 0.9rem;
}
