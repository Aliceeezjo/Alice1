<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>😱 BOO! 😱</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background-color: black;
    }
    img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      object-fit: cover;
      z-index: 999;
    }
  </style>
</head>
<body>
  <img id="scaryImage" src="https://i.imgur.com/2z3fqYk.png" style="display: none;">
  <audio id="screamSound" src="https://www.myinstants.com/media/sounds/movie_1.mp3"></audio>

  <script>
    setTimeout(() => {
      document.getElementById('scaryImage').style.display = 'block';
      document.getElementById('screamSound').play();
    }, 1000);
  </script>
</body>
</html>
