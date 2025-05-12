<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Selamat Ulang Tahun!</title>
  <style>
    /* Dasar halaman dan layout */
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #ffb6c1, #ffe4e1);
      font-family: 'Arial Black', sans-serif;
      text-align: center;
      overflow: hidden;
      max-width: 350px;
      height: 600px;
      margin-left: auto;
      margin-right: auto;
      position: relative;
      user-select: none;
    }

    h1 {
      font-size: 2.5em;
      margin-top: 50px;
      color: #d6336c;
      animation: fadeIn 2s ease-in-out;
      padding: 0 10px;
    }

    p {
      font-size: 1.3em;
      color: #333;
      margin: 20px 10px;
      animation: fadeIn 3s ease-in-out;
    }

    /* Foto container dengan 3 gambar */
    .foto-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 30px auto;
      flex-wrap: nowrap;
      overflow: hidden;
      max-width: 350px;
      padding: 0 10px;
    }

    .foto-container img {
      width: 90px;
      height: 160px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s;
      flex-shrink: 0;
    }

    .foto-container img:hover {
      transform: scale(1.1);
    }

    /* Animasi elemen jatuh (balon, pita, dll) */
    .falling-item {
      position: absolute;
      width: 60px;
      height: 60px;
      opacity: 0.9;
      user-select: none;
      pointer-events: none;
      animation-name: fall;
      animation-timing-function: linear;
      animation-iteration-count: 1;
      animation-fill-mode: forwards;
    }

    @keyframes fall {
      0% { transform: translateY(-100px); }
      100% { transform: translateY(600px); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 1.1em;
      border: none;
      background-color: #ff69b4;
      color: white;
      border-radius: 10px;
      cursor: pointer;
      animation: fadeIn 4s ease-in-out;
      user-select: none;
      transition: background-color 0.3s, transform 0.2s;
      box-shadow: 0 4px 10px rgba(255,105,180,0.6);
    }

    button:hover {
      background-color: #e754a1;
      transform: scale(1.05);
    }

    /* Wrapper video fullscreen yang muncul menutupi halaman */
    #video-wrapper {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(0, 0, 0, 0.9);
      justify-content: center;
      align-items: center;
      animation: fadeInSlide 0.8s ease forwards;
      z-index: 10000;
      user-select: none;
    }

    #video-wrapper.fadeOut {
      animation: fadeOutSlide 0.8s ease forwards;
    }

    /* Video dengan aspek rasio 9:16, portrait */
    #video {
      height: 90vh;
      max-height: 90vh;
      width: auto;
      max-width: calc(90vh * 9 / 16);
      border-radius: 20px;
      box-shadow: 0 0 25px rgba(255, 105, 180, 0.9);
      background: black;
    }

    /* Animasi muncul dengan gerakan slide ke bawah + fade in */
    @keyframes fadeInSlide {
      0% {
        opacity: 0;
        transform: translateY(-30px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Animasi hilang dengan gerakan slide ke atas + fade out */
    @keyframes fadeOutSlide {
      0% {
        opacity: 1;
        transform: translateY(0);
      }
      100% {
        opacity: 0;
        transform: translateY(-30px);
      }
    }

    /* Reset for smaller screens for perfect fit */
    @media (max-width: 350px) {
      body {
        max-width: 350px;
        height: 600px;
        overflow: hidden;
      }
    }
  </style>
</head>
<body>
  <h1>Selamat Ulang Tahun, Cintaku!</h1>
  <p>Semoga kamu selalu bahagia dan impianmu tercapai ya!</p>

  <div class="foto-container" aria-label="Foto Pacar">
    <img src="foto1.jpg" alt="Foto Pacar 1" />
    <img src="foto2.jpg" alt="Foto Pacar 2" />
    <img src="foto3.jpg" alt="Foto Pacar 3" />
  </div>

  <button id="toggleVideoBtn" aria-expanded="false" aria-controls="video-wrapper" aria-label="Tampilkan video kejutan ulang tahun">Klik disini</button>

  <div id="video-wrapper" role="dialog" aria-modal="true" aria-hidden="true" aria-labelledby="videoTitle">
    <video id="video" src="gacor.mp4" type="video/mp4" controls playsinline></video>
  </div>

  <script>
    const imagesFalling = ['balon2.png', 'pita.png', 'balon12.png'];

    function createFallingItem() {
      const fallingItem = document.createElement('img');
      fallingItem.src = imagesFalling[Math.floor(Math.random() * imagesFalling.length)];
      fallingItem.className = 'falling-item';
      fallingItem.style.left = Math.random() * 100 + 'vw';
      fallingItem.style.animationDuration = (Math.random() * 3 + 2) + 's';

      document.body.appendChild(fallingItem);

      fallingItem.addEventListener('animationend', () => {
        fallingItem.remove();
      });
    }

    function createMultipleFallingItems(count) {
      for (let i = 0; i < count; i++) {
        setTimeout(createFallingItem, i * 300); // stagger start times
      }
    }

    // Auto start falling items continuously
    createMultipleFallingItems(10);
    setInterval(() => {
      createMultipleFallingItems(10);
    }, 5000);

    const btn = document.getElementById('toggleVideoBtn');
    const videoWrapper = document.getElementById('video-wrapper');
    const video = document.getElementById('video');

    btn.addEventListener('click', () => {
      if (videoWrapper.style.display === 'flex') {
        // Mulai animasi fade out dan sembunyikan video setelah selesai animasi
        videoWrapper.classList.add('fadeOut');
        video.pause();
        video.currentTime = 0;
        btn.disabled = true; // blok tombol selama animasi

        setTimeout(() => {
          videoWrapper.style.display = 'none';
          videoWrapper.classList.remove('fadeOut');
          btn.textContent = 'Klik disini';
          btn.setAttribute('aria-expanded', 'false');
          btn.disabled = false;
        }, 800);
      } else {
        // Tampilkan video dengan animasi fade in
        videoWrapper.style.display = 'flex';
        btn.textContent = 'Tutup video';
        btn.setAttribute('aria-expanded', 'true');
        // Autoplay video saat muncul
        video.play();
      }
    });

    // Accessibility: close video dengan tombol ESC
    document.addEventListener('keydown', (e) => {
      if (e.key === "Escape" && videoWrapper.style.display === 'flex') {
        btn.click();
      }
    });
  </script>
</body>
</html>