<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>月光 - Clair de Lune</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: #0f0f0f;
      color: #ddd;
      font-family: system-ui, -apple-system, sans-serif;
      display: grid;
      place-items: center;
    }
    .player {
      width: 320px;
      padding: 2.5rem 1.8rem;
      background: #111;
      border-radius: 12px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.7);
    }
    h1 {
      margin: 0 0 1.8rem;
      font-size: 1.4rem;
      font-weight: 400;
      text-align: center;
      letter-spacing: 2px;
      color: #ccc;
    }
    .controls {
      display: flex;
      align-items: center;
      gap: 1.2rem;
      margin-bottom: 1.6rem;
    }
    button {
      width: 64px;
      height: 64px;
      border: none;
      border-radius: 50%;
      background: #2a2a2a;
      color: white;
      font-size: 1.8rem;
      cursor: pointer;
      transition: all 0.18s;
    }
    button:hover { background: #3a3a3a; transform: scale(1.08); }
    button:active { transform: scale(0.96); }
    .progress-container {
      height: 6px;
      background: #333;
      border-radius: 3px;
      margin: 1.2rem 0;
      cursor: pointer;
      position: relative;
    }
    .progress {
      height: 100%;
      width: 0%;
      background: #7a9fff;
      border-radius: 3px;
      pointer-events: none;
    }
    .time {
      display: flex;
      justify-content: space-between;
      font-size: 0.78rem;
      color: #888;
      margin-bottom: 1.4rem;
    }
    .volume-container {
      display: flex;
      align-items: center;
      gap: 1rem;
    }
    .volume-container span {
      font-size: 0.9rem;
      min-width: 36px;
      color: #aaa;
    }
    input[type="range"] {
      -webkit-appearance: none;
      height: 5px;
      background: #444;
      border-radius: 3px;
      outline: none;
      flex: 1;
    }
    input[type="range"]::-webkit-slider-thumb {
      -webkit-appearance: none;
      width: 14px;
      height: 14px;
      background: #7a9fff;
      border-radius: 50%;
      cursor: pointer;
    }
    input[type="range"]::-moz-range-thumb {
      width: 14px;
      height: 14px;
      background: #7a9fff;
      border: none;
      border-radius: 50%;
      cursor: pointer;
    }
  </style>
</head>
<body>

<div class="player">
  <h1>Clair de Lune</h1>
  
  <div class="controls">
    <button id="playPauseBtn">▶</button>
  </div>

  <div class="progress-container" id="progressContainer">
    <div class="progress" id="progress"></div>
  </div>

  <div class="time">
    <span id="currentTime">0:00</span>
    <span id="duration">0:00</span>
  </div>

  <div class="volume-container">
    <span>音量</span>
    <input type="range" id="volume" min="0" max="1" step="0.01" value="0.7">
  </div>
</div>

<audio id="audio" preload="auto">
  <source src="https://www.orangefreesounds.com/wp-content/uploads/2018/01/Clair-de-lune-piano.mp3" type="audio/mpeg">
  你的瀏覽器不支援 audio 元素。
</audio>

<script>
  const audio = document.getElementById('audio');
  const playPauseBtn = document.getElementById('playPauseBtn');
  const progressContainer = document.getElementById('progressContainer');
  const progress = document.getElementById('progress');
  const currentTimeEl = document.getElementById('currentTime');
  const durationEl = document.getElementById('duration');
  const volumeSlider = document.getElementById('volume');

  function formatTime(seconds) {
    const min = Math.floor(seconds / 60);
    const sec = Math.floor(seconds % 60);
    return `${min}:${sec.toString().padStart(2, '0')}`;
  }

  audio.addEventListener('timeupdate', () => {
    const percent = (audio.currentTime / audio.duration) * 100;
    progress.style.width = `${percent}%`;
    currentTimeEl.textContent = formatTime(audio.currentTime);
  });

  audio.addEventListener('loadedmetadata', () => {
    durationEl.textContent = formatTime(audio.duration);
  });

  progressContainer.addEventListener('click', (e) => {
    const rect = progressContainer.getBoundingClientRect();
    const pos = (e.clientX - rect.left) / rect.width;
    audio.currentTime = pos * audio.duration;
  });

  playPauseBtn.addEventListener('click', () => {
    if (audio.paused) {
      audio.play();
      playPauseBtn.textContent = '❚❚';
    } else {
      audio.pause();
      playPauseBtn.textContent = '▶';
    }
  });

  volumeSlider.addEventListener('input', () => {
    audio.volume = volumeSlider.value;
  });

  audio.addEventListener('ended', () => {
    playPauseBtn.textContent = '▶';
  });
</script>

</body>
</html>
