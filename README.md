<!DOCTYPE html>
<html>
<head>
<title>Dragon with MATRIX on its chest</title>
<style>
  body {
    background-color: #1F2937;
    color: #F8F8F2;
    font-family: 'Courier New', Courier, monospace;
  }
  .dragon {
    position: relative;
    width: 100%;
    padding-top: 56.25%; /* 16:9 aspect ratio */
  }
  .dragon > img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  .matrix {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 72px;
    font-weight: bold;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  }
</style>
</head>
<body>
<div class="dragon">
  <img src="dragon.png" alt="Dragon">
  <div class="matrix">MATRIX</div>
</div>
</body>
</html>
