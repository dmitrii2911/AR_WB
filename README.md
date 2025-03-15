<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3D Model with AR</title>
  <script type="module" src="https://cdn.jsdelivr.net/npm/@google/model-viewer@2.0.0/dist/model-viewer.min.js"></script>
</head>
<body>

  <h1>Смотрите 3D модель в дополненной реальности</h1>

  <model-viewer src="https://raw.githubusercontent.com/username/3d-models/main/model.glb"
                alt="3D Model"
                auto-rotate
                camera-controls
                ar
                ar-modes="webxr scene-viewer quick-look"
                style="width: 100%; height: 500px;">
  </model-viewer>

</body>
</html>
