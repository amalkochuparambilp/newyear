<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Background</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
    }

    video {
      position: fixed;
      top: 50%;
      left: 50%;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      transform: translateX(-50%) translateY(-50%);
      z-index: -1;
    }
  </style>
</head>
<body>
  <video autoplay muted loop>
    <source src="your-video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <!-- Your content goes here -->
</body>
</html>