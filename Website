<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Am I the Best?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #333;
    }
    button {
      font-size: 18px;
      padding: 10px 20px;
      margin: 10px;
      border: none;
      background-color: #4CAF50;
      color: white;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #45a049;
    }
    #no-btn {
      position: absolute;
    }
  </style>
</head>
<body>
  <h1>Am I, Lakshya, the most handsome, smart, and caring man in the world?</h1>
  <button onclick="yesClicked()">Yes</button>
  <button id="no-btn" onmouseover="moveButton()">No</button>

  <script>
    function yesClicked() {
      document.body.innerHTML = "<h1>I knew it! Thanks for agreeing. You're amazing too!</h1>";
    }

    function moveButton() {
      const button = document.getElementById("no-btn");
      const x = Math.random() * (window.innerWidth - button.offsetWidth);
      const y = Math.random() * (window.innerHeight - button.offsetHeight);
      button.style.left = x + "px";
      button.style.top = y + "px";
    }
  </script>
</body>
</html>
