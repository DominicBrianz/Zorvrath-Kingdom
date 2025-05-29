<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zorvrath Kingdom</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- Header -->
  <header class="bg-gray-800 p-6 shadow-lg">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold text-purple-400">Zorvrath Kingdom</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-purple-300">About</a>
        <a href="#factions" class="hover:text-purple-300">Factions</a>
        <a href="#gallery" class="hover:text-purple-300">Gallery</a>
        <a href="#contact" class="hover:text-purple-300">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-gradient-to-b from-gray-900 to-gray-800">
    <h2 class="text-5xl font-extrabold text-purple-500 mb-4">Welcome to Zorvrath</h2>
    <p class="text-xl text-gray-300 mb-6">A realm of ancient power, epic legends, and mystical factions.</p>
    <a href="#about" class="bg-purple-600 hover:bg-purple-700 px-6 py-3 rounded-xl text-white font-semibold">Explore Kingdom</a>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 px-6 bg-gray-800">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-purple-400 mb-4">About Zorvrath</h3>
      <p class="text-gray-300">Zorvrath is a vast and mystical kingdom filled with diverse lands, legendary beasts, and powerful magic. It has stood for millennia, divided into noble houses and ancient factions vying for control and peace.</p>
    </div>
  </section>

  <!-- Factions Section -->
  <section id="factions" class="py-16 px-6 bg-gray-900">
    <div class="max-w-6xl mx-auto">
      <h3 class="text-3xl font-bold text-center text-purple-400 mb-10">Factions</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold text-purple-300 mb-2">The Flameborn</h4>
          <p class="text-gray-400">Warriors of fire and fury, descendants of the Phoenix Order.</p>
        </div>
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold text-purple-300 mb-2">Lunaris Circle</h4>
          <p class="text-gray-400">Mystic sages guided by moonlight and ancient celestial magic.</p>
        </div>
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold text-purple-300 mb-2">The Ironfang</h4>
          <p class="text-gray-400">Savage and honorable clan of beast-tamers and mountain guardians.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="py-16 px-6 bg-gray-800">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-purple-400 mb-4">Gallery</h3>
      <p class="text-gray-400 mb-6">Visuals from the kingdom (Coming Soon)</p>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <div class="bg-gray-700 h-32 rounded-lg animate-pulse"></div>
        <div class="bg-gray-700 h-32 rounded-lg animate-pulse"></div>
        <div class="bg-gray-700 h-32 rounded-lg animate-pulse"></div>
        <div class="bg-gray-700 h-32 rounded-lg animate-pulse"></div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="085648147385" class="py-16 px-6 bg-gray-900">
    <div class="max-w-md mx-auto text-center">
      <h3 class="text-3xl font-bold text-purple-400 mb-4">Contact</h3>
      <p class="text-gray-400 mb-6">Want to join Zorvrath? Send us a message.</p>
      <form class="space-y-4">
        <input type="text" placeholder="Tathe Surya" class="w-full p-3 rounded-lg bg-gray-800 text-white placeholder-gray-500">
        <input type="email" placeholder="dominic1brianz@gmail.com" class="w-full p-3 rounded-lg bg-gray-800 text-white placeholder-gray-500">
        <textarea placeholder="Your Message" class="w-full p-3 rounded-lg bg-gray-800 text-white placeholder-gray-500 h-32"></textarea>
        <button type="submit" class="w-full bg-purple-600 hover:bg-purple-700 p-3 rounded-lg font-semibold">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-center py-6">
    <p class="text-gray-500">&copy; 2025 Zorvrath Kingdom. All rights reserved.</p>
  </footer>

</body>
</html>