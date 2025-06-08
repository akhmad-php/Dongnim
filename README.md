# Dongnim
Webview frontend Dongnim
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dongnim</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #121212;
      color: #fff;
    }

    header {
      background-color: #1f1f1f;
      padding: 1em;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .profile {
      display: flex;
      align-items: center;
    }

    .profile img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      margin-right: 10px;
    }

    .video-list {
      padding: 1em;
    }

    .video-item {
      background-color: #2a2a2a;
      margin-bottom: 1em;
      padding: 1em;
      border-radius: 8px;
    }

    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: #1f1f1f;
      display: flex;
      justify-content: space-around;
      padding: 0.5em 0;
    }

    .nav-item {
      color: #bbb;
      font-size: 0.9em;
      text-align: center;
    }

    .nav-item.active {
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <div class="profile">
      <img src="https://via.placeholder.com/40" alt="User">
      <span>Hi, User</span>
    </div>
  </header>

  <main class="video-list">
    <div class="video-item">Episode 1: Awal Cerita</div>
    <div class="video-item">Episode 2: Konflik Muncul</div>
    <div class="video-item">Episode 3: Puncak Emosi</div>
  </main>

  <footer>
    <div class="nav-item active">🏠<br>Home</div>
    <div class="nav-item">📅<br>Jadwal</div>
    <div class="nav-item">🔤<br>A-Z</div>
    <div class="nav-item">📚<br>Library</div>
    <div class="nav-item">👤<br>Profil</div>
  </footer>

</body>
</html>
