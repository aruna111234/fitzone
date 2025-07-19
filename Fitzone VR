<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FitZone VR</title>
  <style>
    body {
      margin: 0;
      background: #000;
      font-family: Arial, sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .panel {
      background: #1e1e1e;
      border: 2px solid #00ffc8;
      border-radius: 16px;
      padding: 30px;
      text-align: center;
      box-shadow: 0 0 25px #00ffc8;
      color: white;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 25px;
    }

    button {
      background: #00ffc8;
      color: #000;
      border: none;
      padding: 15px 20px;
      margin: 10px 0;
      border-radius: 10px;
      font-size: 16px;
      width: 100%;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }

    button:hover {
      background: #00e6b0;
      transform: scale(1.05);
    }

    .music-controls {
      position: absolute;
      bottom: 15px;
      left: 15px;
    }

    .music-controls button {
      padding: 8px 12px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <div class="panel">
    <h1>🏋️‍♂️ FitZone VR</h1>
    <button onclick="startWorkout()">Start Workout</button>
    <button onclick="openSettings()">Settings</button>
    <button onclick="exitApp()">Exit</button>
  </div>

  <!-- Music Controls -->
  <div class="music-controls">
    <button onclick="playMusic()">▶️ Music</button>
    <button onclick="pauseMusic()">⏸️</button>
  </div>

  <!-- Background Music -->
  <audio id="bg-music" autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-dubstep.mp3" type="audio/mpeg">
    Your browser does not support audio.
  </audio>

  <script>
    const music = document.getElementById('bg-music');

    function startWorkout() {
      alert("🚀 Workout Started! Time to sweat!");
      music.play();
    }

    function openSettings() {
      alert("⚙️ Settings will be available soon!");
    }

    function exitApp() {
      if (confirm("❌ Do you want to exit the app?")) {
        alert("Goodbye 👋");
      }
    }

    function playMusic() {
      music.play();
    }

    function pauseMusic() {
      music.pause();
    }
  </script>

</body>
</html>
