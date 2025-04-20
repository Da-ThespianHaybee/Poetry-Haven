<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Poetry Haven</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      background-color: #f9f4f0;
      color: #333;
    }header {
  background-color: #c97c5d;
  color: white;
  padding: 1.5rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  margin: 0;
  font-size: 2rem;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 1.2rem;
  font-weight: bold;
}

.hero {
  background-color: #fbe9e7;
  padding: 4rem 2rem;
  text-align: center;
}

.hero h2 {
  font-size: 2.2rem;
  margin-bottom: 0.5rem;
  color: #5d4037;
}

.hero p {
  font-size: 1.1rem;
  color: #6d4c41;
}

.poems {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  padding: 2rem;
}

.poem-card {
  background: white;
  border-radius: 10px;
  padding: 1.5rem;
  box-shadow: 0 4px 10px rgba(0,0,0,0.07);
  transition: transform 0.3s ease;
}

.poem-card:hover {
  transform: translateY(-5px);
}

.poem-card h3 {
  margin-top: 0;
  color: #8d6e63;
}

.poem-card p {
  font-style: italic;
  color: #4e342e;
}

footer {
  background: #c97c5d;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

  </style>
</head>
<body>
  <header>
    <h1>Poetry Haven</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Poems</a>
      <a href="#">Collections</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>  <section class="hero">
    <h2>Where Words Breathe & Feelings Flow</h2>
    <p>Discover verses that touch the soul and ignite the mind. Welcome to your poetic sanctuary.</p>
  </section>  <section class="poems">
    <div class="poem-card">
      <h3>Queue of Injustice</h3>
      <p>"We line in shadows, unheard and undone, seeking light that never comes..."</p>
    </div>
    <div class="poem-card">
      <h3>Labor of Triumph</h3>
      <p>"Through sweat and struggle, hope becomes the harvest of the broken..."</p>
    </div>
    <div class="poem-card">
      <h3>Sleepless Night</h3>
      <p>"Whispers of worry, echoing loud, in the chamber of a weary soul..."</p>
    </div>
    <div class="poem-card">
      <h3>Creator’s Gift</h3>
      <p>"To breathe, to feel, to dream—how divine the ordinary becomes..."</p>
    </div>
  </section>  <footer>
    <p>&copy; 2025 Poetry Haven. All rights reserved.</p>
  </footer>
</body>
</html>
