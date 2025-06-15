<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PSMK-DIKPORA-DIY</title>
  <link rel="icon" href="https://static.vecteezy.com/system/resources/previews/016/716/181/large_2x/website-3d-icon-png.png" type="image/x-icon">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
      font-family: sans-serif;
    }
    .iframe-container {
      position: relative;
      width: 100%;
      height: 100vh;
    }
    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }
    .loader {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 1.2rem;
      color: #666;
      z-index: 10;
    }
  </style>
</head>
<body>
  <div class="iframe-container">
    <div class="loader" id="loader">Loading app...</div>
    <iframe 
      src="https://script.google.com/macros/s/AKfycbzedXmIWX87HBe-KivxN45hypBeJXIlrqTozGTV2sDgD8ax4DanIeH808zV1x5cLRRT/exec" 
      title="JNCfy Web App"
      onload="document.getElementById('loader').style.display='none';"
      allowfullscreen>
    </iframe>
  </div>
</body>
</html>

