[index.html.txt](https://github.com/user-attachments/files/25377561/index.html.txt)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday My Love ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: #fff;
      text-align: center;
      overflow-x: hidden;
    }

    .container {
      padding: 40px 20px;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: auto;
      animation: fadeIn 3s ease-in-out;
    }

    .heart {
      font-size: 2em;
      animation: float 2s infinite ease-in-out;
    }

    @keyframes float {
      0%,100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 40px;
      padding: 0 20px;
    }

    .gallery img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .message-box {
      margin-top: 50px;
      background: rgba(255,255,255,0.15);
      padding: 25px;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      opacity: 0.8;
    }
  </style>
</head>

<body>

  <div class="container">

    <h1>Happy Birthday My Love 🎂❤️</h1>

    <p>
      From the moment you came into my life, everything became more beautiful.
      Today is your special day, and I wanted to make you something unique…
      just like you 💖
    </p>

    <div class="heart">💕 💕 💕</div>

    <!-- PHOTO GALLERY -->
    <div class="gallery">
      <!-- Replace image links with your photos -->
      <img src="photo1.jpg" alt="Us 1">
      <img src="photo2.jpg" alt="Us 2">
      <img src="photo3.jpg" alt="Us 3">
      <img src="photo4.jpg" alt="Us 4">
    </div>

    <!-- LOVE MESSAGE -->
    <div class="message-box">
      <h2>A Message For You 💌</h2>
      <p>
        You are my happiness, my peace, and my favorite person in the world.
        Thank you for every smile, every hug, and every memory we share.
        I love you more than words can explain ❤️
      </p>
    </div>

    <footer>
      Made with love by adam 💕
    </footer>

  </div>

</body>
</html>
