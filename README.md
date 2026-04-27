<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Juan Duarte | Desarrollador</title>

<style>
:root {
    --bg: #0d1117;
    --card: #161b22;
    --primary: #58a6ff;
    --text: #c9d1d9;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: var(--bg);
    color: var(--text);
}

/* NAV */
nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    position: sticky;
    top: 0;
    background: rgba(13,17,23,0.9);
    backdrop-filter: blur(10px);
}

nav h2 {
    color: var(--primary);
}

nav a {
    color: var(--text);
    text-decoration: none;
    margin-left: 20px;
}

/* HERO */
.hero {
    text-align: center;
    padding: 80px 20px;
}

.hero img {
    width: 160px;
    border-radius: 15px;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: 2.5rem;
    color: var(--primary);
}

.hero p {
    margin-top: 10px;
    font-size: 1.1rem;
}

/* BOTÓN */
.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background: var(--primary);
    color: black;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
}

/* SECCIONES */
.section {
    padding: 60px 10%;
    text-align: center;
}

.section h2 {
    margin-bottom: 20px;
    color: var(--primary);
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: var(--card);
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

/* TECNOLOGÍAS */
.tech span {
    display: inline-block;
    margin: 8px;
    padding: 8px 12px;
    background: var(--card);
    border-radius: 5px;
}

/* CONTACTO */
.contact a {
    display: inline-block;
    margin: 10px;
    padding: 10px 15px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
}

.linkedin { background: #0077B5; }
.gmail { background: #D14836; }
.whatsapp { background: #25D366; }

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    font-size: 14px;
    opacity: 0.7;
}

/* RESPONSIVE */
@media (max-width: 600px) {
    .hero h1 {
        font-size: 2rem;
    }
}
</style>

</head>

<body>

<!-- NAV -->
<nav>
    <h2>Juan Duarte</h2>
    <div>
        <a href="#sobre">Sobre mí</a>
        <a href="#skills">Tecnologías</a>
        <a href="#contacto">Contacto</a>
    </div>
</nav>

<!-- HERO -->
<section class="hero">
    <img src="https://liderazgoempresarial.info/wp-content/uploads/unnamed-file-1075.jpeg" alt="Perfil">
    <h1>Hola, soy Juan Duarte 👋</h1>
    <p>Desarrollador enfocado en soluciones prácticas y eficientes</p>
    <a href="#contacto" class="btn">Contáctame</a>
</section>

<!-- SOBRE MÍ -->
<section id="sobre" class="section">
    <h2>👨🏻‍💻 Sobre mí</h2>
    <div class="cards">
        <div class="card">💡 Desarrollo soluciones tecnológicas eficientes</div>
        <div class="card">🎓 Formación continua en software y bases de datos</div>
        <div class="card">🚀 Me gustan los retos y el crecimiento profesional</div>
        <div class="card">👥 Trabajo en equipo y liderazgo</div>
    </div>
</section>

<!-- TECNOLOGÍAS -->
<section id="skills" class="section">
    <h2>🛠 Tecnologías</h2>
    <div class="tech">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>Java</span>
        <span>SQL</span>
        <span>Python</span>
        <span>GitHub</span>
    </div>
</section>

<!-- GITHUB STATS -->
<section class="section">
    <h2>⚙️ GitHub Analytics</h2>
    <img width="45%" src="https://github-readme-stats.vercel.app/api?username=goodRaptor2025&show_icons=true&theme=algolia">
    <img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=goodRaptor2025&layout=compact&theme=algolia">
</section>

<!-- CONTACTO -->
<section id="contacto" class="section">
    <h2>🤝 Contacto</h2>
    <div class="contact">
        <a href="https://linkedin.com/in/Juan Duarte" class="linkedin">LinkedIn</a>
        <a href="mailto:juand081318@gmail.com" class="gmail">Gmail</a>
        <a href="https://wa.me/573238740968" class="whatsapp">WhatsApp</a>
    </div>
</section>

<footer>
    © 2026 Juan Duarte - Portafolio
</footer>

</body>
</html>
