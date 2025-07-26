# Prasanta
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prasanta Bera | Entrepreneur Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --black: #0a0a0a;
      --gold: #d4af37;
      --green: #00ff9c;
      --white: #ffffff;
    }* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: 'Poppins', sans-serif;
  background-color: var(--black);
  color: var(--white);
  line-height: 1.6;
}

header {
  background: linear-gradient(90deg, var(--black), var(--green));
  padding: 3rem 2rem;
  text-align: center;
  color: var(--gold);
}

header h1 {
  font-size: 3rem;
}

header p {
  font-size: 1.2rem;
  margin-top: 0.5rem;
  color: var(--white);
}

section {
  padding: 4rem 2rem;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

section h2 {
  font-size: 2rem;
  color: var(--gold);
  margin-bottom: 1.5rem;
}

.skills, .projects, .contact {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
}

.card {
  background: rgba(255, 255, 255, 0.03);
  padding: 1.5rem;
  border-radius: 12px;
  border: 1px solid var(--green);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
}

.contact a {
  color: var(--green);
  text-decoration: none;
}

footer {
  padding: 2rem;
  text-align: center;
  font-size: 0.9rem;
  background: var(--black);
  color: var(--white);
}

@media(min-width: 768px) {
  .skills, .projects {
    grid-template-columns: repeat(2, 1fr);
  }
}

  </style>
</head>
<body>
  <header>
    <h1>Prasanta Bera</h1>
    <p>Vision-Driven Entrepreneur | Business Strategist | Future Architect</p>
  </header>  <section>
    <h2>About Me</h2>
    <p>I am Prasanta Bera, a visionary entrepreneur shaping the future with strategy, innovation, and relentless execution. I blend deep focus with modern business intelligence to create scalable impact and build tomorrow's empires.</p>
  </section>  <section>
    <h2>What I Do</h2>
    <div class="skills">
      <div class="card">Entrepreneurship – Building scalable businesses from scratch</div>
      <div class="card">Personal Branding – Crafting digital identities that convert</div>
      <div class="card">Creative Strategy – Visual storytelling and content direction</div>
      <div class="card">Market Research – Turning insights into innovation</div>
    </div>
  </section>  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <strong>Startup Builder</strong><br>
