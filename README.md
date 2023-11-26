<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Secret Box</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
    }

    #box {
      padding: 20px;
      border: 2px solid #333;
      background-color: #fff;
      text-align: center;
    }

    #secretText {
      display: none;
    }
  </style>
</head>
<body>

<div id="box">
  <button onclick="revealText()">Open the Box</button>
  <p id="secretText">FUCK YOU</p>
</div>

<script>
  function revealText() {
    document.getElementById('secretText').style.display = 'block';
  }
</script>

</body>
</html>
