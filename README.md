<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mit Portfolio</title>
    <style>
        body {
            font-family: 'Futura PT', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img, .gallery video {
            width: 48%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            max-width: 600px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            margin: 10px 0;
            font-size: 16px;
            width: 100%;
        }
        .contact-form button {
            padding: 10px;
            background-color: #444;
            color: #fff;
            border: none;
            font-size: 18px;
            cursor: pointer;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        .social-links a {
            color: #fff;
            font-size: 24px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mit Portfolio</h1>
    </header>
    <nav>
        <a href="#about">Om mig</a>
        <a href="#projects">Projekter</a>
        <a href="#cv">CV</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <section id="about">
        <h2>Om mig</h2>
        <p>Velkommen til mit portfolio! Jeg er en passioneret content creator med erfaring inden for grafik, foto og video. Jeg elsker at skabe og dele mit arbejde med verden.</p>
    </section>
    <section id="projects">
        <h2>Projekter</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/400" alt="Projekt billede">
            <img src="https://via.placeholder.com/400" alt="Projekt billede">
            <video controls>
                <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                Din browser understøtter ikke video-tagget.
            </video>
            <img src="https://via.placeholder.com/400" alt="Projekt billede">
        </div>
    </section>
    <section id="cv">
        <h2>CV</h2>
        <p>Her kommer information om min erhvervserfaring, uddannelse og færdigheder. (Dette kan udvides med flere detaljer som du ønsker.)</p>
    </section>
    <section id="contact">
        <h2>Kontakt</h2>
        <form class="contact-form">
            <input type="text" placeholder="Dit navn" required>
            <input type="email" placeholder="Din email" required>
            <textarea placeholder="Din besked" rows="5" required></textarea>
            <button type="submit">Send</button>
        </form>
        <div class="social-links">
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        </div>
        <p>Email: din.email@example.com</p>
        <p>Telefon: +45 1234 5678</p>
    </section>
    <footer>
        <p>&copy; 2024 Dit Navn. Alle rettigheder forbeholdes.</p>
    </footer>
</body>
</html>
