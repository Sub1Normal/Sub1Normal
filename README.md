<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Página Emo</title>
  <style>
    body {
      background: url('https://i.ibb.co/DRr3Vmh/skulls-hearts.png') repeat;
      color: white;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      display: flex;
      width: 90%;
      margin: auto;
    }

    /* Sidebar */
    .sidebar {
      background: #a50000;
      padding: 15px;
      width: 250px;
      min-height: 100vh;
    }

    .sidebar h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .sidebar img {
      width: 100%;
      border: 2px solid black;
    }

    /* Contenido principal */
    .content {
      flex: 1;
      background: #111;
      padding: 20px;
    }

    .content h1 {
      background: #a50000;
      padding: 10px;
      font-size: 22px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
      margin-top: 15px;
    }

    .gallery img {
      width: 100%;
      border: 2px solid #a50000;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Lado izquierdo -->
    <div class="sidebar">
      <h2>Mi Perfil</h2>
      <img src="https://i.ibb.co/DY2w8Zz/emo-avatar.jpg" alt="Avatar">
      <p>Estado: 💀 Listening to Asking Alexandria 💀</p>
    </div>

    <!-- Contenido principal -->
    <div class="content">
      <h1>Galería Emo</h1>
      <div class="gallery">
        <img src="https://i.ibb.co/jWsw6KM/emo1.jpg" alt="img1">
        <img src="https://i.ibb.co/gd6Hg1T/emo2.jpg" alt="img2">
        <img src="https://i.ibb.co/DY2w8Zz/emo-avatar.jpg" alt="img3">
        <img src="https://i.ibb.co/6w7hPm2/emo3.jpg" alt="img4">
      </div>
    </div>
  </div>
</body>
</html>
