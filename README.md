# -www.hk-business-solutions.netlify.app
git clone <https://github.com/><<h1>Inline HTML heading</h1>>/hk-business-solutions.git
<!DOCTYPE html>
<html lang="fr">
<head>
   <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HK Business Solutions</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" preload>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<header>
    <!-- HK signifie Hassanal Koné -->
    HK Business Solutions – Prospection & Relation Client
    <p>"Accompagner les TPE, PME et indépendants à se lancer est notre raison de vivre"</p>
</header>
<section>
    <h1>Développez votre clientèle sans alourdir votre charge de travail</h1>
    <p>Nous accompagnons les PME, TPE et indépendants dans leur prospection commerciale et gestion de la relation client.</p>
    <button id="contactButton">Contactez-nous</button>
</section>
<section>
    <h2>À propos</h2>
    <p>HK Business Solutions est née de la volonté d'aider les entreprises à maximiser leur potentiel commercial grâce à des solutions de prospection externalisée adaptées à leurs besoins.</p>
</section>
<section>
 <h2>Localisation</h2>
    <iframe
        width="100%"
        height="300"
        frameborder="0"
        style="border:0"
        allowfullscreen
        src="https://www.google.com/maps/embed/v1/place?key=YOUR_GOOGLE_MAPS_API_KEY&q=Le+Mans,France">
    </iframe>
</section>
<section>
    <h2>Contactez-nous</h2>
    <form id="contactForm">
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message :</label>
        <textarea id="message" name="message" required></textarea><br>
        <button type="submit">Envoyer</button>
    </form>
</section>
<footer>
      <div class="mt-6">
        <p class="text-lg text-green-700 mb-2">Suivez-nous sur les réseaux sociaux :</p>
        <div class="flex justify-center gap-4">
          <a href="https://www.facebook.com" target="_blank" class="text-green-700 hover:text-green-900">Facebook</a>
          <a href="https://www.linkedin.com" target="_blank" class="text-green-700 hover:text-green-900">LinkedIn</a>
          <a href="https://www.instagram.com" target="_blank" class="text-green-700 hover:text-green-900">Instagram</a>
        </div>
      </div>
      <div class="mt-10">
        <h2 class="text-2xl font-semibold text-green-800 mb-4">Contactez-nous</h2>
        <form class="flex flex-col gap-4">
          <input type="text" placeholder="Nom" class="p-2 rounded-lg border border-green-300" />
          <input type="email" placeholder="Email" class="p-2 rounded-lg border border-green-300" />
          <textarea placeholder="Message" class="p-2 rounded-lg border border-green-300" rows="4"></textarea>
          <button type="submit" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg">Envoyer</button>
        </form>
      </div>
    </div>
  </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  .min-h-screen {
    min-height: 100vh;
  }
  
  .bg-gradient-to-b {
    background: linear-gradient(to bottom, #daf7a6, #c8e6c9);
  }
  
  .text-center {
    text-align: center;
  }
  
  .text-4xl {
    font-size: 2.5rem;
  }
  
  .font-bold {
    font-weight: bold;
  }
  
  .mb-6 {
    margin-bottom: 1.5rem;
  }
  
  .text-green-800 {
    color: #2e7d32;
  }
  
  .shadow-lg {
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
  }
  
  .rounded-2xl {
    border-radius: 1rem;
  }
  
  .bg-white {
    background-color: #ffffff;
  }
  
  .p-6 {
    padding: 1.5rem;
  }
  
  .text-lg {
    font-size: 1.125rem;
  }
  
  .mb-4 {
    margin-bottom: 1rem;
  }
  
  .text-green-700 {
    color: #388e3c;
  }
  
  .bg-green-600 {
    background-color: #43a047;
  }
  
  .hover\:bg-green-700:hover {
    background-color: #388e3c;
  }
  
  .text-white {
    color: #ffffff;
  }
  
  .px-4 {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  
  .py-2 {
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
  }
  
  .rounded-lg {
    border-radius: 0.5rem;
  }
  
  .mt-10 {
    margin-top: 2.5rem;
  }
  
  .text-2xl {
    font-size: 1.5rem;
  }
  
  .font-semibold {
    font-weight: 600;
  }
  
  .list-disc {
    list-style-type: disc;
  }
  
  .list-inside {
    list-style-position: inside;
  }
  
  .mb-10 {
    margin-bottom: 2.5rem;
  }
  
  .italic {
    font-style: italic;
  }
  
  .rounded-2xl {
    border-radius: 1rem;
  }
  
  .shadow-lg {
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
  }
  
  .mt-6 {
    margin-top: 1.5rem;
  }
  
  .gap-4 {
    gap: 1rem;
  }
  
  .flex {
    display: flex;
  }
  
  .justify-center {
    justify-content: center;
  }
  
  .border {
    border-width: 1px;
  }
  
  .border-green-300 {
    border-color: #81c784;
  }
  git add .
git commit -m "Initial commit"
git push origin main
