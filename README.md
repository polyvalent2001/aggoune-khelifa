# aggoune-khelifa
just do this 

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ton Nom | Star Officielle</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d0d0d;
      color: #fff;
      scroll-behavior: smooth;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.8);
      padding: 15px 0;
      text-align: center;
      z-index: 1000;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ffcc00;
    }

    header {
      height: 100vh;
      background: linear-gradient(to right, #1e1e1e, #333), url('iamge/ak16.jpg') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding-top: 60px;
    }

    header h1 {
      font-size: 4em;
      color: #ffcc00;
      text-shadow: 0 0 10px #000;
    }

    header p {
      font-size: 1.5em;
      margin-top: 15px;
    }

    section {
      padding: 80px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .section-title {
      font-size: 2.5em;
      margin-bottom: 20px;
      color: #ffcc00;
      text-align: center;
    }

    .about p,
    .contact p {
      font-size: 1.2em;
      line-height: 1.6;
      color: #ddd;
      text-align: center;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .gallery img {
      width: 250px;
      height: 350px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(255, 204, 0, 0.3);
      transition: transform 0.5s ease;
    }

    .gallery img:hover {
      transform: perspective(600px) rotateY(15deg) scale(1.05);
      box-shadow: 0 20px 40px rgba(255, 204, 0, 0.5);
    }

    footer {
      background: #111;
      text-align: center;
      padding: 30px;
      color: #aaa;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5em;
      }

      .gallery img {
        width: 90%;
        height: auto;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Accueil</a>
    <a href="#about">À propos</a>
    <a href="#gallery">Galerie</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Accueil -->
  <header id="home">
    <h1>🌤️ AGGOUNE KHELIFA ❤️ __polyvalent__✨</h1>
    <p>Athlete et Coach 🏊‍♂️ Swimmer(nageur)🏃‍♂️Runner(coureur)🚴‍♂️Cyclist(cycliste) </p>
  </header>

  <!-- À propos -->
  <section id="about" class="about">
    <h2 class="section-title">À propos de moi</h2>
    <p>
    Hello!
My name is khelifa, and I am a high-level athlete specializing in cycling, running, and swimming. 🚴‍♂️🏃‍♂️🏊‍♂️ With years of dedication and passion, I train hard every day to push my limits and achieve excellence in all disciplines. I compete at national and international levels, always striving for personal bests and team success.
I believe in discipline, resilience, and continuous improvement—qualities that have helped me overcome challenges and reach my goals. Sports is not just a passion; it’s my lifestyle and my motivation to inspire others.
I’m excited to connect with fellow athletes, coaches, and enthusiasts to share experiences and grow together.
Let’s ride, run, and swim towards success! 💪 </p>
  </section>

  <!-- Galerie -->
  <section id="gallery">
    <h2 class="section-title">Ma Galerie</h2>
    <div class="gallery">
      <img src="ak (15).jpg" alt="Photo 1">
      <img src="ak (4).png" alt="Photo 2">
      <img src="ak (14).jpg" alt="Photo 3">
      <img src="ak (12).jpg" alt="Photo 4">
      <img src="ak (3).jpg"  alt="Photo 5">
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2 class="section-title">Contact</h2>
    <p>
      📩 Pour me contacter :  
      <br>
      <a href="mailto:manageraggounekhelifa@gmail.com" style="color: #ffcc00;">manageraggounekhelifa@gmail.com</a>
      <br><br>
      📱 Suivez-moi sur Instagram :  
      <br>
      <a href="https://instagram.com/tonpseudo" target="_blank" style="color: #ffcc00;">@tonpseudo</a>
    </p>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Ton Nom Officiel | Tous droits réservés
  </footer>

</body>
</html>
